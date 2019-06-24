---
id: doc2
title: Player
sidebar_label: Usage
---

## List all Players

<!--DOCUSAURUS_CODE_TABS-->
<!--Example-->
```js
axios.get('https://blackstarsapi.herokuapp.com/api/players');
```

<!--Response-->
```json
[
    {
        "_id": "5d0cdb9618fc05072c6bba39",
        "name": "Asamoah Gyan",
        "photo": "http://res.cloudinary.com/tutcan/image/upload/v1561128149/w79vyeszxbmqamwjc9dv.jpg",
        "jersey": 3,
        "position": "str",
        "caps": 32,
        "club": "Udinese",
        "info": "Updated info on Asamoah Gyan",
        "__v": 0
    },
    {
        "_id": "5d0cdbc018fc05072c6bba3a",
        "name": "Andre Dede Ayew",
        "photo": "http://res.cloudinary.com/tutcan/image/upload/v1561123985/v9dqgmtrd2gzacjysu2g.jpg",
        "jersey": 23,
        "position": "mid",
        "caps": 17,
        "club": "Udinese",
        "info": "Info about Andre Dede Ayew",
        "__v": 0
    },
    {
        "_id": "5d0cdbdf18fc05072c6bba3b",
        "name": "Samuel Inkoom",
        "photo": "http://res.cloudinary.com/tutcan/image/upload/v1561124015/prvpaw9w5wsik9rzqnuy.jpg",
        "jersey": 5,
        "position": "def",
        "caps": 18,
        "club": "Udinese",
        "info": "Info about Samuel Inkoom",
        "__v": 0
    },
    {
        "_id": "5d0d05a0b091c42ab4fdfee4",
        "name": "Christian Atsu",
        "photo": "http://res.cloudinary.com/tutcan/image/upload/v1561134704/aqsn2nl6ng29vrfko1c4.jpg",
        "jersey": 6,
        "position": "def",
        "caps": 18,
        "club": "Udinese",
        "info": "Info about Samuel Inkoom",
        "__v": 0
    }
]
```
<!--END_DOCUSAURUS_CODE_TABS-->

## List a single Player by jersey number

<!--DOCUSAURUS_CODE_TABS-->
<!--Example-->
```js
axios.get('https://blackstarsapi.herokuapp.com/api/players/jersey/3');
```

<!--Response-->
```json
{
    "_id": "5d0cdb9618fc05072c6bba39",
    "name": "Asamoah Gyan",
    "photo": "http://res.cloudinary.com/tutcan/image/upload/v1561128149/w79vyeszxbmqamwjc9dv.jpg",
    "jersey": 3,
    "position": "str",
    "caps": 32,
    "club": "Udinese",
    "info": "Updated info on Asamoah Gyan",
    "__v": 0
}
```
<!--END_DOCUSAURUS_CODE_TABS-->


This is a link to [another document.](doc3.md)  
This is a link to an [external page.](http://www.example.com)
