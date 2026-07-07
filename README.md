# 🤖 AI Automation Lab

AI와 다양한 API 및 서비스를 연동하여 반복 업무를 자동화하는 워크플로우를 구현하고 기록하는 저장소입니다.

---

## 🚀 Current Workflow

### AI News Automation

Google News RSS를 주기적으로 수집하고, Gemini를 활용해 뉴스를 요약한 뒤 업무 자동화 아이디어를 생성하여 Notion 데이터베이스에 자동 저장하는 워크플로우입니다.

### Workflow

```text
RSS Feed Trigger
        ↓
Check Duplicate (Notion)
        ↓
Gemini
        ↓
Save to Notion
```

---

## ✨ Features

- [x] Google News RSS 자동 수집
- [x] 5분 주기 자동 실행
- [x] Gemini를 활용한 뉴스 요약
- [x] 뉴스 기반 업무 자동화 아이디어 생성
- [x] Notion 데이터베이스 자동 저장
- [x] Notion 기반 중복 뉴스 검사

---

## 🛠 Tech Stack

| Category | Stack |
|----------|-------|
| Workflow | n8n |
| AI | Google Gemini API |
| Database | Notion API |
| Data Source | Google News RSS |

---

## 📄 Demo

### Workflow

> n8n Workflow

<img width="1259" height="555" alt="Image" src="https://github.com/user-attachments/assets/55a280c2-9917-4f6e-83c0-a3839b698e2a" />

### Result

> Notion Database

https://hammerhead-knuckle-22a.notion.site/3961dbafa868805abd67dd33b3f4eae5?v=3961dbafa86880c1b146000c91cc7016&source=copy_link

---

## 📌 Roadmap

- [ ] Gmail 자동 메일 발송
- [ ] Slack 알림 연동
- [ ] Discord 알림 연동
- [ ] GitHub Issue 자동 생성
- [ ] AI Daily Report 생성
- [ ] 여러 RSS Source 통합
- [ ] 뉴스 카테고리 자동 분류
- [ ] 중요 뉴스 우선순위 분석

---

## 📂 Repository Structure

```text
.
├── README.md
├── docker-compose.yml
├── workflows/
│   └── ai-news-automation.json
├── screenshots/
│   ├── workflow.png
│   └── notion-result.png
└── n8n_data/
```