# Alchemist

```bash
.
├── README.md
└── data
    ├── list.json
    └── detail.json
```

## list.json

목록 데이터

```json
[
  {
    "cover": "https://image.aladin.co.kr/product/1795/53/cover200/8925892898_1.jpg",
    "title": "강철의 연금술사 완전판 1",
    "detail": "https://raw.githubusercontent.com/adothis/docs/main/data/detail.json",
    "top": "만화 top1 2주",
    "writer": "아라카와 히로무",
    "picture":"아라카와 히로무"
  },
  ...
]
```

## detail.json

1개의 상품 데이터 예제

```json
{
  "isbn": 9788925892894,
  //초판, 2rd, 3rd, 완전판
  "edition": [9788925886862],
  //세트 도서에 포함된 경우
  "set": [6000679882, 9788925892900],

  "store": {
    "aladin": {
      "url": "https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=17955391",
      "soldOut": false
    },
    "yes24": {
      "url": "http://www.yes24.com/Product/Goods/7269207",
      "soldOut": false
    },
    "ridibooks": {
      "url": "https://ridibooks.com/books/505010468",
      "soldOut": false
    }
  },

  "book": {
    //제목
    "title": "강철의 연금술사",
    //작가
    "author": {
      //지은이
      "writer": ["아라카와 히로무"],
      //그림
      "picture": ["아라카와 히로무"],
      //원작자
      "original": [],
    },
    //출판사
    "publisher": "학산문화사",
    //출판일
    "date": "2012-07-16",
    //표지
    "cover": "https://image.aladin.co.kr/product/1795/53/cover500/8925892898_1.jpg",
    //판매 통화
    "currency": "원",
    //정가
    "regular": 9500,
    //판매가
    "selling": 8550
  },
  // 랭킹 그때 그때 데이터가 달라서 분리 해서 기록이 필요
  "ranking": {
    "weekly": 79,
    "top100": 11,
    "salesPoint": 2620
  },
  //장르
  "genre": [
    ["본경장르만화", "판타지", "액션판타지"],
    ["본경장르만화", "SF/가상사회"]
  ],
  //구매가 분표
  "buyer": [
    { "age": 10, "woman": 7.6, "man": 5.8 },
    { "age": 20, "woman": 25.2, "man": 20.4 },
    { "age": 30, "woman": 9.0, "man": 14.1 },
    { "age": 40, "woman": 8.6, "man": 5.3 },
    { "age": 50, "woman": 1.9, "man": 1.6 },
    { "age": 60, "woman": 0.3, "man": 0.2 }
  ],
  //평가 분포
  "star": {
    "average": 8.7,
    "all": [{ "5": 45.5 }, { "4": 45.5 }, { "3": 9.1 }, { "2": 0 }, { "1": 0 }]
  }
}

```
