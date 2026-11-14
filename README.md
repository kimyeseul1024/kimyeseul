# kimyeseul
sj sw mom
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>안내 페이지</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Apple SD Gothic Neo", "Pretendard", sans-serif;
      background-color: #f4f6f9;
      color: #333;
      line-height: 1.6;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }
    .container {
      background: #ffffff;
      max-width: 600px;
      width: 100%;
      padding: 40px 30px;
      border-radius: 16px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.06);
    }
    .badge {
      display: inline-block;
      background: #e8f0fe;
      color: #1a73e8;
      font-size: 13px;
      font-weight: 600;
      padding: 4px 12px;
      border-radius: 20px;
      margin-bottom: 16px;
    }
    h1 {
      font-size: 26px;
      font-weight: 700;
      margin-bottom: 12px;
      color: #111;
    }
    p.subtitle {
      font-size: 15px;
      color: #666;
      margin-bottom: 28px;
    }
    .info-box {
      background: #f8f9fa;
      border-left: 4px solid #1a73e8;
      padding: 16px 20px;
      border-radius: 8px;
      margin-bottom: 24px;
    }
    .info-box h2 {
      font-size: 16px;
      margin-bottom: 8px;
      color: #222;
    }
    .info-box ul {
      list-style: none;
      font-size: 14px;
      color: #555;
    }
    .info-box ul li {
      margin-bottom: 6px;
    }
    .btn {
      display: block;
      width: 100%;
      text-align: center;
      background: #1a73e8;
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      padding: 14px;
      border-radius: 10px;
      transition: background 0.2s;
    }
    .btn:hover {
      background: #1557b0;
    }
    footer {
      margin-top: 24px;
      text-align: center;
      font-size: 12px;
      color: #999;
    }
  </style>
</head>
<body>

  <div class="container">
    <span class="badge">공지 및 안내</span>
    <h1>프로젝트 안내 페이지</h1>
    <p class="subtitle">방문해 주셔서 감사합니다. 주요 일정 및 이용 방법을 아래에서 확인해 주세요.</p>

    <div class="info-box">
      <h2>주요 안내 사항</h2>
      <ul>
        <li>• <strong>일시:</strong> 2026년 11월 20일 (금) 오후 2시</li>
        <li>• <strong>장소:</strong> 온라인 및 지정 안내 장소</li>
        <li>• <strong>문의:</strong> contact@example.com</li>
      </ul>
    </div>

    <!-- 이동할 링크가 있다면 href="#"의 # 대신 주소를 넣으세요 -->
    <a href="#" class="btn">자세히 보기 / 신청하기</a>

    <footer>
      © 2026 All Rights Reserved.
    </footer>
  </div>

</body>
</html>
