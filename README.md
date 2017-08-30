## Simple object oriented web-scraper
Grabs zip files from the included URI, decompresses them, and publishes them to redis list.
  
# Example Usage:
    s = Scraper.new(limit: 1)
    s.extract_zip()
    s.push_xml_to_redis()
