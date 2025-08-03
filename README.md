# 🛡️ 웹 해킹 시뮬레이터: XSS & SQLi 체험 도구  
# 🛡️ Web Hacking Simulator: Experience XSS & SQL Injection

## 1. 프로젝트 개요 | Project Overview

이 프로젝트는 웹 해킹의 대표적인 취약점인 XSS와 SQL Injection을 직접 체험하고  
그 원리와 방어법을 학습할 수 있는 웹 기반 시뮬레이터입니다.  
보안에 대한 기초 지식이 없는 사용자도 이해할 수 있도록 쉽게 구성하는 것이 목표입니다.

This project is a web-based simulator that allows users to experience  
common web vulnerabilities such as XSS and SQL Injection.  
It aims to be simple and educational, even for those with no security background.

---

## 2. 주요 기능 | Main Features

### ✅ XSS 시뮬레이터 | XSS Simulator
- 사용자가 `<script>alert('XSS')</script>` 입력 → DOM 조작 확인  
- 공격 전/후 화면 비교 제공

- Users can input `<script>alert('XSS')</script>` and observe DOM changes  
- Compare the interface before and after the attack

---

### ✅ SQL Injection 시뮬레이터 | SQL Injection Simulator
- `' OR '1'='1` 입력으로 로그인 우회 실습  
- 필터링 유무에 따른 반응 차이 시각화

- Practice login bypass with inputs like `' OR '1'='1`  
- Visualize the difference with/without input filtering

---

### ✅ 대응 가이드 | Defense Guide
- 각 공격에 대한 방어 방법 설명  
- 예: 입력 정제, Prepared Statement 등

- Explains defense techniques for each attack  
- e.g., Input sanitizing, prepared statements, etc.

---

## 3. 사용 기술 (예정) | Tech Stack (Planned)

| 분야 | 기술 | Area | Technology |
|------|------|------|------------|
| 프론트엔드 | HTML, CSS, JavaScript | Frontend | HTML, CSS, JavaScript |
| 백엔드 | Flask 또는 Node.js | Backend | Flask or Node.js |
| 배포 | GitHub Pages, Render | Deployment | GitHub Pages, Render |

---

## 4. 기대 효과 | Expected Outcomes

- 보안의 원리를 직접 체험할 수 있는 웹 도구 제작  
- 포트폴리오와 블로그에 활용 가능  

- A hands-on web tool to understand web security fundamentals  
- Can be used for portfolio and blog content  

---

## 5. 일정 계획 | Project Timeline

| 날짜 | 목표 | Date | Goal |
|------|------|------|------|
| 8/3 | 기획서 작성 완료 | Aug 3 | Complete project planning |
| 8/5~10 | XSS 기능 개발 | Aug 5–10 | Build XSS module |
| 8/11~15 | SQLi 기능 개발 | Aug 11–15 | Build SQL Injection module |
| 8/16~20 | 대응 가이드 제작 | Aug 16–20 | Add defense guide |
| 8/21 | 배포 및 블로그 작성 | Aug 21 | Deploy and write blog post |

---

## 📌 만든 사람 | Made by

- 이름 Name: Eden (Jimin Eom)
- 이메일 E-mail: eomjimin0711@gmail.com
- 블로그 Blog: (추후 연결 예정)

---


