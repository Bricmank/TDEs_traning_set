# TDEs_traning_set
Provides a code to simulate LSST observed TDE light curves from existing events.

The events are MOSFiT fits in LSST bands to TDE fits (to real data) provided by Matt. Some of the LSST fits could be improved.

The notebook provides the metric (with prepeak, some_color and some_color_pu requirements) and then saves the prepeak (most simple requirement) light curves to the prepeak directory. One can also output the more sophisticated light curves (some_color and some_color_pu, but note that some_color and some_color_pu directories should be created beforehand in the working directory).
