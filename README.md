### Michigan Sailing Club weewx configuration

**[Visit the live site](http://mscwx.andyfowler.com/).**

This is the configuration for a [weewx](http://www.weewx.com/) installation, running on a Raspberry Pi, at the [Michigan Sailing Club](http://michigansailingclub.org/). It's powered by a Davis Vantage Pro2, installed at the end of the dock.

### Testing and contributing

I need to shore up these instructions, but you can develop the skin from a local weewx installation pretty easily. Edit the `weewx.conf` file to use the simulator to get some fake data, disable the rsync reports, and run `./bin/wee_reports weewx.conf`

Help wanted!