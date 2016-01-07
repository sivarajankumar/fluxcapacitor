# Bug fixes #

  * **Issue** **28**: _polyA tails intermediary to transcript sequence_<br><a href='http://code.google.com/p/fluxcapacitor/issues/detail?id=28'>http://code.google.com/p/fluxcapacitor/issues/detail?id=28</a></li></ul>

<ul><li><b>Issue</b> <b>29</b>: <i>Simulator cannot handle identical transcript IDs</i><br><a href='http://code.google.com/p/fluxcapacitor/issues/detail?id=29'>http://code.google.com/p/fluxcapacitor/issues/detail?id=29</a></li></ul>

# Enhancements #

  * _Limited poly-A tail length_: length distribution is cut at maximum known adenylation polymer. This is a temporary solution, the fragmentation initiation step may become slower.

# Incompatibilities #

  * Library (.lib) files of version 20100330 and earlier are incompatible due to the changes necessary to solve [Issue 28](https://code.google.com/p/fluxcapacitor/issues/detail?id=28).