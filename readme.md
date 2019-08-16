Repository Init Content
=======================

Test using swagger.

<strong>URL</strong>: http://localhost:8080/kie-server/docs/#/KIE%20session%20assets/manageContainer<br/>
<strong>ContainerID</strong>: VariousMultipleTracker_1.0.0

```json
{
        "lookup": "variousmultipletracker-stateful-kie-session",
        "commands": [
                {
                        "insert": {
                                "object": {
                                        "com.myspace.variousmultipletracker.ComparableFirm": {
                                                "price": 150.03,
                                                "noOfShares": 215.6,
                                                "eps": 0.51,
                                                "rps": 8.72,
                                                "bvps": 8.93,
                                                "ocps": 1.56,
                                                "rdps": 5.55,
                                                "symbol" : "VTX"
                                    
                                        }
                                },
                                "out-identifier": "comparableFirm"
                        }
                },
                {
                        "insert": {
                                "object": {
                                        "com.myspace.variousmultipletracker.TargetFirm": {
                                                "price": 0,
                                                "noOfShares": 259.19,
                                                "eps": 8.09,
                                                "rps": 11.75,
                                                "bvps": 17.11,
                                                "ocps": 4.90,
                                                "randd": 5.46,
                                                "symbol" : "VTX"
                                        }
                                },
                                "out-identifier": "targetFirm"
                        }
                },
                {
                        "fire-all-rules": {}
                },
                {
                        "get-objects": {
                                "out-identifier": "objects"
                        }
                },
                {
                        "dispose": {}
                }
        ]
}
```
