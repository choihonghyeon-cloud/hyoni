# hyoni
온라인학교 시간표 작성 웹사이트

효니/
├── README.md
└── index.html   ← 여기에 방금 만든 코드 넣기!

<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>2025학년도 2학기 시간표 신청</title>
  <style>
    body {
      font-family: "Noto Sans KR", sans-serif;
      margin: 0;
      background-color: #ffffff;
      text-align: center;
    }
    header {
      background-color: #1a3d1a;
      color: white;
      padding: 16px 0;
      font-size: 1.5em;
      font-weight: bold;
    }
    section {
      padding: 20px;
      line-height: 1.7;
      color: #333;
    }
    .buttons {
      margin: 20px 0;
    }
    button {
      background-color: #4c8c4a;
      color: white;
      border: none;
      padding: 14px 36px;
      font-size: 1.1em;
      border-radius: 6px;
      margin: 10px;
      cursor: pointer;
      box-shadow: 3px 3px 0px #264d27;
      transition: 0.2s;
    }
    button:hover {
      background-color: #3d733b;
      transform: translateY(-2px);
    }
    .note {
      font-size: 0.9em;
      color: #444;
      margin-top: 8px;
    }
    .logo {
      margin-top: 30px;
    }
    .logo img {
      max-width: 260px;
      height: auto;
    }
    footer {
      margin-top: 10px;
      color: #333;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>2025학년도 2학기 시간표 신청</header>

  <section>
    <p>본 프로그램은 2025학년도 2학기 시간표 작성을 위해 참여학교별로 운영됩니다.</p>
    <p>각 학교의 개설 과목을 확인하고, 신청한 후 ‘시간표 신청 확인’을 통해 내용을 점검할 수 있습니다.</p>

    <div class="buttons">
      <button onclick="alert('학교별 개설 과목 페이지로 이동 예정')">학교별 개설 과목</button>
      <button onclick="alert('시간표 신청 확인 페이지로 이동 예정')">시간표 신청 확인</button>
    </div>

    <div class="note">
      ※ 특이사항이 발생할 경우 경남온라인학교로 문의 바랍니다. ☎ 055)230-8332
    </div>

    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Gyeongnam_Online_School_logo.png/320px-Gyeongnam_Online_School_logo.png" alt="경남온라인학교 로고" />
      <p style="color:#0c7b9a; font-weight:bold;">Gyeongnam Online School</p>
    </div>
  </section>

  <footer>© 2025 Gyeongnam Online School</footer>
</body>
</html>
