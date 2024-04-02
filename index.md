<img src="images/logo.png" align="right" height="100"/>

# About

*Traffic-Taffy tools perform differential network traffic anomaly analysis.*

# Further information:

* The [github source repository](https://github.com/traffic-taffy/traffic-taffy)
* [Usage documentation](https://traffic-taffy.readthedocs.io/en/latest/)
    * [A worked usage case study](https://traffic-taffy.readthedocs.io/en/latest/casestudy.html)
    * [Getting started information](https://traffic-taffy.readthedocs.io/en/latest/gettingstarted.html)
* The [pypi page](https://pypi.org/project/traffic-taffy/)

# Presentations about traffic-taffy:

* DNS-OARC 42: [Video](https://www.youtube.com/watch?v=5CG-RZhzNBM)
  and [slides](https://indico.dns-oarc.net/event/48/contributions/1034/attachments/999/1968/oarc42-hardaker-taffy.pdf)

# Major ChangeLog events

- 0.8.5:
    - Added support for reporting a number of IANA numeric->name translations

- 0.8:
    - Note that the -x switch to limit the list of results has been moved to -R.
    - Added ip2asn and psl (public suffix list) extra processing modules that can be enabled with a new -x switch.
    - Added a --merge command line option to merge all dissected traffic traces into a single time-stream.  For taffy-compare, this forces comparison by time bins across all supplied data.
    - All labeling switched to underbar separators rather that period separators to support future expression handling.


- 0.7: 
    - Support for comparing multiple files via time ranges rather than comparing file vs file.  Use --merge to enable this.

- 0.6: support added for analyzing [dnstap](https://dnstap.info/) files
