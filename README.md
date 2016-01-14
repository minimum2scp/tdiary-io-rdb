# TDiary::IO::Rdb

[![Gem Version](https://badge.fury.io/rb/tdiary-io-rdb.png)](https://rubygems.org/gems/tdiary-io-rdb) [![Build Status](https://secure.travis-ci.org/tdiary/tdiary-io-rdb.png)](https://travis-ci.org/tdiary/tdiary-io-rdb)

RDB like sqlite, mysql and postgresql adapter for tDiary

## Installation

Add this line to your tDiary's Gemfile.local:

    gem 'tdiary-io-rdb'

And then execute:

    $ bundle

## Usage

Add follow snipet to your tdiary.conf

```ruby
@io_class = TDiary::IO::Rdb
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
