# Contract Interface Model Language (CIML)

- ***<u>Contract Interface Model Language</u>*** - **(CIML)** is a UI File used for blokchain Dapps to compile their user interface within a mobile or web app on demand this json file follows a strict set of rules to allow for dynamic compiling of user interfaces into a multitude of devices which have adopted the framework.




# CIML File

```json
// CIML Basic Format | Simple Interface Contracts generated by file onto multiple device types | Mobile, Web, Tablet

{
  "cimlVersion": "1.0.1",
  "appVersion": "0.0.1",
  "contractLanguage": "solidity ^0.8.10",
  "network":"XDC",
  "name": "LedgerContract",
  "symbol": "LC",
  "logo": "https\\:ipfs.address.url.jpeg",
  "thumbnail": "https\\:ipfs.address.url.jpeg",
  "websitelink":"https\\:DAppletSite.com",
  "description": "This is the description of the Dapp provided",
  "contractMainnet": "xdcerG45fCgvgh&%vhvctcr678BB",
  "contractTestnet":"xdcers4d5fr6t7y8uj98ugyftghdw2",
  "screenShots":[""],
  "variables": [],
  "functions": [],
  "objects": [],
  "views": [],
  "metadata": []
}

```
# CIML DApplet Examples






# CIML Document Example 2 = Form
```json
[
  {
    "cimlVersion": "1.0.1",
    "appVersion": "0.0.1",
    "contractLanguage": "solidity ^0.8.10",
    "name": "Test2",
    "symbol": "LC",
    "logo": "https\\:ipfs.address.url.jpeg",
    "thumbnail": "https\\:ipfs.address.url.jpeg",
    "websitelink":"https\\:DAppletSite.com",
    "cimlURL":"https\\:DAppletSite.com/ciml",
    "description": "This is the description of the Dapp provided",
    "networks":["XDC"],
    "contractMainnet": ["xdcerG45fCgvgh&%vhvctcr678BB"],
    "screenShots":[""],
    "abi": "func1(uint _count)",
    "byteCode": "--bytes--",
    "variables": [
      {
        "name": "text1",
        "type": "String",
        "value": "Example 2"
      },
      {
        "name": "background",
        "type": "1",
        "value": "#008000"
      },
      {
        "name": "button1",
        "type": "value",
        "value": "Submit Form"
      }
    ],
    "functions": [""],
    "objects": [
        {
          "name": "text1",
          "type": "text", 
          "value": "this is the else statement",
          "foreGroundColor":".black",
          "font":"headlines",
          "frame":[100,50],
          "alignment":"center",
          "backgroundColor":".white",
          "cornerRadius":0.0,
          "bold":false,
          "fontWeight":"regular",
          "shadow":0.0,
          "padding":20
      },
      {
        "name": "textField1",
        "type": "textField", 
        "value": "this is a text feild",
        "textField": "enter info",
        "foreGroundColor":".gray",
        "frame":[300,50],
        "alignment":"center",
        "backgroundColor":".white",
        "cornerRadius":10.0,
        "shadow":10.0,
        "padding":20
    },
    {
      "name": "textField2",
      "type": "textField", 
      "value": "this is a text feild",
      "textField": "enter data field 2",
      "foreGroundColor":".gray",
      "frame":[300,50],
      "alignment":"center",
      "backgroundColor":".white",
      "cornerRadius":10.0,
      "shadow":10.0,
      "padding":20
  },
  {
    "name": "textField3",
    "type": "textField", 
    "value": "this is a text feild",
    "textField": "enter info textField 3",
    "foreGroundColor":".gray",
    "frame":[300,50],
    "alignment":"center",
    "backgroundColor":".white",
    "cornerRadius":10.0,
    "shadow":10.0,
    "padding":20
},
    {
      "name": "icon1",
      "type": "sysimage", 
      "value": "gear",
      "foregroundcolor":".black",
      "frame":[100,50],
      "padding":20
  },
  {
    "name": "button1",
    "type": "button", 
    "value": "var1",
    "foreGroundColor":".black",
    "font":"headlines",
    "frame":[200,50],
    "alignment":"center",
    "backgroundColor":".white",
    "cornerRadius":10.0,
    "bold":false,
    "fontWeight":"regular",
    "shadow":0.0,
    "padding":20
}
    ],
    "views": [
      {
        "View": 0,
        "Object": "text1",
        "location": 5
      },
      {
        "View": 0,
        "Object": "textField1",
        "location": 32
      },
      {
        "View": 0,
        "Object": "textField2",
        "location": 50
      },
      {
        "View": 0,
        "Object": "textField3",
        "location": 68
      },
      {
        "View": 0,
        "Object": "icon1",
        "location": 9
      },
      {
        "View": 0,
        "Object": "button1",
        "location": 122
      }
    ],
    "metadata": [
      "Top Descriptor",
      "xdc",
      "document",
      "test"
    ]
  }
]


```
