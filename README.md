# Azure AI Hackathon 2021 - Utilize Azure Cognitive Service Computer Vision API to Analyze an Image

## Steps to Run
- npm install
- ADD Azure Computer Vision Key and Endpoint URL in src/azure-cognitiveservices-computervision.js
- npm start

## test result
```javascript
{
  "URL": "https://i.ytimg.com/vi/fIZR5Ib1p_w/maxresdefault.jpg",
  "categories": [
    {
      "name": "people_many",
      "score": 0.828125,
      "detail": {
        "celebrities": []
      }
    }
  ],
  "adult": {
    "isAdultContent": false,
    "isRacyContent": false,
    "isGoryContent": false,
    "adultScore": 0.002180637326091528,
    "racyScore": 0.004463532939553261,
    "goreScore": 0.0000021140515400475124
  },
  "color": {
    "dominantColorForeground": "Brown",
    "dominantColorBackground": "Brown",
    "dominantColors": [
      "Brown"
    ],
    "accentColor": "B15E1A",
    "isBWImg": false,
    "isBwImg": false
  },
  "imageType": {
    "clipArtType": 0,
    "lineDrawingType": 0
  },
  "tags": [
    {
      "name": "grass",
      "confidence": 0.9999966025352478
    },
    {
      "name": "soccer",
      "confidence": 0.9999958872795105,
      "hint": "sport"
    },
    {
      "name": "person",
      "confidence": 0.9996789693832397
    },
    {
      "name": "playing",
      "confidence": 0.9990330934524536
    },
    {
      "name": "ball",
      "confidence": 0.9984008073806763
    },
    {
      "name": "field",
      "confidence": 0.9980970621109009
    },
    {
      "name": "outdoor",
      "confidence": 0.9714146852493286
    },
    {
      "name": "football",
      "confidence": 0.9708915948867798
    },
    {
      "name": "young",
      "confidence": 0.9660767316818237
    },
    {
      "name": "game",
      "confidence": 0.9467827081680298
    },
    {
      "name": "group",
      "confidence": 0.9285913705825806
    },
    {
      "name": "sports equipment",
      "confidence": 0.9206110835075378
    },
    {
      "name": "athletic game",
      "confidence": 0.8722784519195557,
      "hint": "sport"
    },
    {
      "name": "playground",
      "confidence": 0.7468779683113098
    },
    {
      "name": "player",
      "confidence": 0.7438602447509766
    },
    {
      "name": "sport",
      "confidence": 0.7184016704559326
    },
    {
      "name": "soccer ball",
      "confidence": 0.6012717485427856
    },
    {
      "name": "boy",
      "confidence": 0.590964138507843
    },
    {
      "name": "match",
      "confidence": 0.3794039487838745
    },
    {
      "name": "stadium",
      "confidence": 0.15041756629943848
    }
  ],
  "description": {
    "tags": [
      "grass",
      "soccer",
      "person",
      "playing",
      "ball",
      "field",
      "outdoor",
      "young",
      "game",
      "group",
      "athletic game",
      "player",
      "sport",
      "match",
      "stadium"
    ],
    "captions": [
      {
        "text": "a group of kids playing football",
        "confidence": 0.5178843140602112
      }
    ]
  },
  "faces": [
    {
      "age": 22,
      "gender": "Female",
      "faceRectangle": {
        "left": 942,
        "top": 140,
        "width": 62,
        "height": 62
      }
    },
    {
      "age": 7,
      "gender": "Male",
      "faceRectangle": {
        "left": 26,
        "top": 83,
        "width": 52,
        "height": 52
      }
    }
  ],
  "objects": [
    {
      "rectangle": {
        "x": 574,
        "y": 536,
        "w": 129,
        "h": 135
      },
      "object": "soccer ball",
      "confidence": 0.779,
      "parent": {
        "object": "sports ball",
        "confidence": 0.876
      }
    },
    {
      "rectangle": {
        "x": 801,
        "y": 17,
        "w": 122,
        "h": 266
      },
      "object": "person",
      "confidence": 0.761
    },
    {
      "rectangle": {
        "x": 1122,
        "y": 59,
        "w": 113,
        "h": 258
      },
      "object": "person",
      "confidence": 0.85
    },
    {
      "rectangle": {
        "x": 0,
        "y": 42,
        "w": 111,
        "h": 472
      },
      "object": "person",
      "confidence": 0.839
    },
    {
      "rectangle": {
        "x": 324,
        "y": 129,
        "w": 265,
        "h": 287
      },
      "object": "shirts",
      "confidence": 0.584
    },
    {
      "rectangle": {
        "x": 811,
        "y": 153,
        "w": 298,
        "h": 288
      },
      "object": "shirts",
      "confidence": 0.742
    },
    {
      "rectangle": {
        "x": 765,
        "y": 365,
        "w": 225,
        "h": 133
      },
      "object": "Shorts",
      "confidence": 0.551
    },
    {
      "rectangle": {
        "x": 238,
        "y": 27,
        "w": 409,
        "h": 649
      },
      "object": "person",
      "confidence": 0.916
    },
    {
      "rectangle": {
        "x": 697,
        "y": 71,
        "w": 509,
        "h": 609
      },
      "object": "person",
      "confidence": 0.894
    }
  ],
  "brands": [],
  "requestId": "b1cc38a5-309c-4197-a162-85e022f924fe",
  "metadata": {
    "width": 1280,
    "height": 720,
    "format": "Jpeg"
  },
  "text": {
    "version": "3.0.0",
    "readResults": [
      {
        "page": 1,
        "language": "en",
        "angle": 17.889,
        "width": 1280,
        "height": 720,
        "unit": "pixel",
        "lines": [
          {
            "boundingBox": [
              934,
              248,
              1043,
              284,
              1036,
              310,
              925,
              275
            ],
            "text": "FORSPORT",
            "words": [
              {
                "boundingBox": [
                  940,
                  250,
                  1042,
                  286,
                  1036,
                  309,
                  931,
                  277
                ],
                "text": "FORSPORT",
                "confidence": 0.638
              }
            ]
          },
          {
            "boundingBox": [
              418,
              233,
              519,
              242,
              517,
              266,
              416,
              256
            ],
            "text": "FORSPON",
            "words": [
              {
                "boundingBox": [
                  419,
                  233,
                  520,
                  244,
                  518,
                  265,
                  416,
                  257
                ],
                "text": "FORSPON",
                "confidence": 0.94
              }
            ]
          }
        ]
      }
    ]
  }
}
```
