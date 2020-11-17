{\rtf1\ansi\ansicpg936\cocoartf1671\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\froman\fcharset0 Times-Roman;\f2\froman\fcharset0 TimesNewRomanPSMT;
}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 ```\
// Bucket operations\
CreateBucket(bucketName)\
DeleteBucket(bucketName)\
ListBuckets()\
\
//Object operations\
\pard\pardeftab720\sl340\sa0\qj\partightenfactor0

\f1\fs28 \cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 GetObject(bucketName, objectPath, offset, length)
\f2 \
\pard\pardeftab720\sl340\sa0\qj\partightenfactor0

\f1 \cf2 PutObject(bucketName, objectPath, data , metadata)
\f2 \

\f1 DeleteObject(bucketName, objectPath)
\f2 \

\f1 ListObjects(bucketName, prefix, startKey, limit, delimiter)
\f2 \
```}