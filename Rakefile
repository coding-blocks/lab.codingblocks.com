require 'rake'

desc 'Preview the site with Jekyll'
task :preview do
    sh "jekyll serve --watch --drafts --baseurl '' --config _config.yml,_config-dev.yml"
end

desc 'Search site and print specific deprecation warnings'
task :check do 
    sh "jekyll doctor"
end

desc 'Create new project'
task :new_project, [:title, :description] do |t, args|
   args.with_defaults(:title => 'New Project', description => '')
   title = args.title
   desc= args.description
   filename = "_posts/#{Time.now.strftime('%Y-%m-%d')}-#{title.downcase.gsub(/&/,'and').gsub(/[,'":\?!\(\)\[\]]/,'').gsub(/[\W\.]/, '-').gsub(/-+$/,'')}.md"
   puts "Creating new page: #{filename}"
   open(filename, 'w') do |post|
     post.puts "---"
     post.puts "layout: post"
     post.puts "permalink:" + " \"projects/" + "#{title.downcase.gsub(/&/,'and').gsub(/[,'":\?!\(\)\[\]]/,'').gsub(/[\W\.]/, '-').gsub(/-+$/,'')}\""
     post.puts "title:" + "\"#{title.gsub(/&/,'&amp;')}\""
     post.puts "description: #{desc}"
     post.puts "categories: project"
     post.puts "date: #{Time.now.strftime('%Y-%m-%d %H:%M:%S %z')}"
     post.puts "tags: []"
     post.puts "---"
   end
end