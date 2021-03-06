# Crawler
## how to execute the spider
iex -S mix
Crawly.Engine.start_spider(BlogSpider)

## Dependencies
def deps do
  [
    {:crawler, "~> 0.1.0"},
    {:floki, "~> 0.26.0"}
  ]
end

## Made with a tutorial called Crawling websites with elixir and crawly (y)