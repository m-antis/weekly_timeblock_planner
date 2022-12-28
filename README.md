# Generate Time-Block Planner Pages

Forked from [drewish's](https://github.com/drewish/planner) take on [Cal Newport's Time-Block Planner](https://www.timeblockplanner.com). This generates a PDF with a week's worth of pages to be editted on a tablet. You can take a look at a [sample](https://github.com/Hyunggilwoo/planner/blob/main/sample.pdf) and see what you think.


## Installation

Assuming you've got [Ruby](http://www.ruby-lang.org/en/) and [Bundler](https://bundler.io)
installed you can just run:
```
git clone git@github.com:Hyunggilwoo/planner.git 
cd planner
bundle install
```

## Usage

It assumes you want to generate pages for the next week so there are no options:
```
./planner.rb
```

You can generate pages for a different weeks by passing in the date:
```
./planner.rb 2022-12-21
```

## Limitations

It probably only works on Ubuntu, but not on other linux distro because I hard coded the Ubuntu font path.
