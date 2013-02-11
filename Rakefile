require "net/http"

task :call_page do
  %w{http://www.herokuapp.com}.each do |url|
    uri = URI.parse(url)
    Net::HTTP.get(uri)
  end
end