# dash-slimframework

dash-slimframework is a docset for [Dash.app][] containing the latest Slim Framework documentation.

![](screenshot.png)

## Installing

Install by opening Dash.app preferences, switch to `Downloads`, click `+`, and enter the feed URL
`https://raw.githubusercontent.com/pfefferle/dash-slimframework/master/Slim_Framework.xml`.

## Build

To rebuild or update this docset run the following commands in the following order:

1. `$ sh sync.sh` to grab the newest version of the documentation
1. `$ python rebuild.py` to generate the docset from the grabbed sources
1. `$ sh pack.sh` to build the tgz file for a new release

## Thanks

The [`sync.sh`][] and [`rebuild.py`][] scripts are based on [@willnorris][]' awesome [RFCDash Docset][] versions.

[Dash.app]: http://kapeli.com/dash
[open an issue]: https://github.com/pfefferle/dash-slimframework/issues
[`pack.sh`]: https://github.com/pfefferle/dash-slimframework/blob/master/pack.sh
[`sync.sh`]: https://github.com/pfefferle/dash-slimframework/blob/master/sync.sh
[`rebuild.py`]: https://github.com/pfefferle/dash-slimframework/blob/master/rebuild.py
[@willnorris]: https://willnorris.com
[RFCDash Docset]: https://github.com/willnorris/rfcdash
