<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>Project README</title>

  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
                   Roboto, "Noto Sans KR", Arial, sans-serif;
      background-color: #ffffff;
      color: #1f2937;
      line-height: 1.6;
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    h1 {
      font-size: 2.2rem;
      margin-bottom: 0.3em;
    }

    h2 {
      font-size: 1.6rem;
      margin-top: 60px;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 8px;
    }

    h3 {
      font-size: 1.3rem;
      margin-top: 40px;
    }

    a {
      color: #2563eb;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .section {
      margin-top: 40px;
    }

    .element {
      margin-top: 50px;
      padding: 30px;
      border: 1px solid #e5e7eb;
      border-radius: 12px;
      background-color: #fafafa;
    }

    .badge-row img {
      height: 28px;
      margin-right: 8px;
      margin-bottom: 6px;
      vertical-align: middle;
    }

    .element-image {
      width: 100%;
      border-radius: 10px;
      margin: 20px 0;
      border: 1px solid #e5e7eb;
    }

    .label {
      font-weight: 600;
      margin-top: 18px;
    }

    .reason {
      background-color: #f3f4f6;
      padding: 15px;
      border-radius: 8px;
      margin-top: 10px;
      font-size: 0.95rem;
    }
  </style>
</head>

<body>

  <!-- Project Title -->
  <h1>
    <a href="https://github.com/username/project-name">
      Project Name
    </a>
  </h1>

  <!-- Purpose -->
  <div class="section">
    <h2>Purpose</h2>
    <p>
      이 프로젝트는 <strong>[해결하고자 한 문제]</strong>를 해결하기 위해  
      <strong>[핵심 기능 또는 접근 방식]</strong>을 제공하는 것을 목적으로 개발되었습니다.
    </p>
  </div>

  <!-- Elements -->
  <div class="section">
    <h2>Elements</h2>

    <!-- Element 1 -->
    <div class="element">
      <h3>Element. 요소명</h3>

      <!-- Tech / Tool -->
      <div class="label">Tech</div>
      <div class="badge-row">
        <img src="https://img.shields.io/badge/JavaScript-000000?style=flat&logo=javascript" />
        <img src="https://img.shields.io/badge/HTML5-000000?style=flat&logo=html5" />
      </div>

      <div class="label">Tool</div>
      <div class="badge-row">
        <img src="https://img.shields.io/badge/VS_Code-000000?style=flat&logo=visualstudiocode" />
        <img src="https://img.shields.io/badge/GitHub-000000?style=flat&logo=github" />
      </div>

      <!-- Reason -->
      <div class="label">Why Tech & Tool</div>
      <div class="reason">
        이 요소는 <strong>[기능 요구 조건]</strong>을 충족해야 했기 때문에  
        <strong>[선택한 기술]</strong>을 사용했습니다.  
        해당 기술은 <strong>[대안 대비 장점]</strong>이라는 장점이 있어 적합하다고 판단했습니다.
      </div>

      <!-- Element Image -->
      <img
        src="./assets/element-example.png"
        alt="element preview"
        class="element-image"
      />

      <!-- Description -->
      <div class="label">Description</div>
      <p>
        이 요소는 <strong>[사용자 행동]</strong>을 통해  
        <strong>[처리 대상]</strong>을 <strong>[결과]</strong>로 변환합니다.  
        이를 통해 사용자는 <strong>[얻게 되는 핵심 가치]</strong>를 경험할 수 있습니다.
      </p>
    </div>

    <!-- Element 추가 가능 -->
  </div>

</body>
</html>
