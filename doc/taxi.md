# APIs

This section lists supported APIs in the KOMN taxi network

## BPP

* Search API should be called to look for taxi availability
* Confirm API should be called to to book the taxi. This API is sync.
* Cancel API should be called to cancel the booking. This API is sync.

More information about the sync APIs can be foud [here](https://github.com/beckn/protocol-specifications/issues/144).

## BAP

* On_search API will be called following search listing available options (vehicle types with prices)
* On_update API will be called for these events that originate at the BPP side:

    * Driver Assigned
    * Ride started
    * Ride completed
    * Ride booking cancelled
