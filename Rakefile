namespace :build do

  desc "Rebuild just the templates, no CSS or JS"
  task :templates do
    `jammit -c config/templates_only.yml`
  end

end

desc "Build the viewer"
task :build do
  `jammit -c config/assets.yml`
end