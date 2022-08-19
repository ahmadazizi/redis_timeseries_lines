# RedisTimeseriesLines

RedisTimeseriesLines is a redis timeseries management system that ties multiple redis timeseries together and let them to be managed as a whole.

Each timeseries is referred to as a `line` of data; so RedisTimelines maintains several lines of timeseries data together. As the result, records consisting of multiple values can be fetched which are incorporated from multiple lines of timeseries with a timestamp in common.

Additionally RedisTimeseriesLines supports two levels of classifiers(c1, c2) to interact with data, plus support for timeframes.