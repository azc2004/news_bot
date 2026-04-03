# news_bot
news bot

# project tree
stock-news-bot/
├── CLAUDE.md
├── .claudeignore
├── .env
├── requirements.txt
├── main.py                  # 스케줄러 진입점
├── collectors/
│   ├── news_collector.py    # 뉴스 수집
│   ├── stock_collector.py   # 주가 데이터 수집
│   └── economic_collector.py # 경제지표 수집
├── analyzers/
│   ├── summarizer.py        # Claude API 요약
│   └── sentiment.py         # 감성 분석
├── publishers/
│   └── telegram_bot.py      # 텔레그램 발송
└── utils/
    ├── scheduler.py
    └── logger.py

    
