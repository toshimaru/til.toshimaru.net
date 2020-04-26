require 'date'

task :til do
  today = Date.today.to_s
  File.write("_posts/#{today}-til.md", <<~YAML)
    ---
    title: #{today}
    ---
  YAML
end
