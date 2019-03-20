# Extracting_from_Live_JSON_Feed
A self-conceived project

A Python script written to access, import and convert data from a publicly available government sponsored binary-formated 'live' JSON feed.
The JSON is tranformed to a dictionary and then selected data is ultimately converted to Python's Pandas.
Rights reserved.

Example porption of the JSON feed in 'readable' binary format:

b'{"type":"FeatureData","metadata":{"reportEpochTime":1534000000,"title":"Extraordinary information","recordsNum":205},"individualRecords":[{"type":"observation","properties":{"foo":12,"bar":30,"foobar":5,"observationEpochTime":1533998000},"where":{"observationType":"singlePoint","coordinates":[37.7749,122.4194]}},{"type":"observation","properties":{"foo":21,"bar":3,"foobar":16,"observationEpochTime":1533998001},"where":{"observationType":"singlePoint","coordinates":[40.7128,74.0060]}},{"type":"observation","properties":{"foo":6,"bar":41,"foobar":41,"observationEpochTime":1533998010},"where":{"observationType":"singlePoint","coordinates":[41.8781,87.6298],...}]}}'


