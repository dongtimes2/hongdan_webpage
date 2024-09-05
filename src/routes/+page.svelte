<script>
  import use1 from '$lib/images/use_1.png';
  import use2 from '$lib/images/use_2.png';
  import use3 from '$lib/images/use_3.png';
  import use4 from '$lib/images/use_4.png';
  import use5 from '$lib/images/use_5.png';
  import use6 from '$lib/images/use_6.png';
  import use7 from '$lib/images/use_7.png';
  import footerBefore from '$lib/images/footer_before.png';
  import footerAfter from '$lib/images/footer_after.png';
  import colorBefore1 from '$lib/images/color_before1.png';
  import colorBefore2 from '$lib/images/color_before2.png';
  import colorAfter1 from '$lib/images/color_after1.png';
  import colorAfter2 from '$lib/images/color_after2.png';
</script>

<div class="area">
  <section class="section">
    <h1 class="section__header">1. 설치방법</h1>
  </section>

  <section class="section">
    <h1 class="section__header">2. 사용방법</h1>
    <div class="section__element">
      <p class="section__content">크롬 브라우저의 상단 바에 위치한 퍼즐 아이콘을 클릭합니다.</p>
      <img class="section__image" src={use1} alt="puzzle icon" />
    </div>
    <div class="section__element">
      <p class="section__content">'확장 프로그램' 리스트 중에서, '홍단'을 찾은 뒤 PIN 아이콘을 클릭합니다.</p>
      <img class="section__image" src={use2} alt="extension list" width="40%" />
    </div>
    <div class="section__element">
      <p class="section__content">'홍단' 아이콘이 상단 바에 고정됩니다.</p>
      <img class="section__image" src={use3} alt="hongdan icon" />
    </div>
    <div class="section__element">
      <p class="section__content">
        '홍익대학교 클래스넷' -> '수강신청' -> '정규학기 수강신청' -> '정규학기 시간표 검색'을 통해 시간표 조회를 할
        경우, 다음 사진과 같이 경쟁률이 표시되게 됩니다.
      </p>
      <img class="section__image" src={use4} alt="class list" width="80%" />
    </div>
    <div class="section__element">
      <p class="section__content">경쟁률 탭에 있는 select box를 클릭함으로써 각 학년별 경쟁률을 파악할 수 있습니다.</p>
      <div class="section__element--row">
        <img class="section__image" src={use5} alt="option list" width="40%" />
        <img class="section__image" src={use6} alt="option list" width="40%" />
      </div>
    </div>
  </section>
  <section class="section">
    <h1 class="section__header">홍익대학교 홈페이지 디자인 변경 기능</h1>
    <div class="section__element">
      <p class="section__content">
        브라우저 상단 바에 있는 '홍단' 아이콘을 클릭하면 다음과 같이, 홍단 프로그램이 표시됩니다.
      </p>
      <p class="section__content">
        여기서 하단에 위치한 체크박스를 클릭함으로써, 학교 홈페이지의 디자인을 변경할 수 있습니다.
      </p>
      <img class="section__image" src={use7} alt="hongdan popup" width="12%" />
    </div>
    <div class="section__element">
      <h2 class="section__sub-header">footer 제거</h2>
      <p class="section__content">클릭할 경우, 홍익대학교 홈페이지 하단을 크게 점유하고 있는 footer가 제거됩니다.</p>
      <p class="section__content--strong">클릭한 이후에 홈페이지를 새로고침해야 적용됩니다.</p>
      <br />
      <p class="section__content">좌: 변경 전, 우: 변경 후</p>
      <div class="section__element--row">
        <img class="section__image" src={footerBefore} alt="footer before" width="45%" />
        <img class="section__image" src={footerAfter} alt="footer after" width="45%" />
      </div>
    </div>
    <div class="section__element">
      <h2 class="section__sub-header">색상 완화</h2>
      <p class="section__content">눈을 아프게 만들었던 홈페이지의 색상을, 부드러운 색으로 변경해줍니다.</p>
      <p class="section__content--strong">클릭한 이후에 홈페이지를 새로고침해야 적용됩니다.</p>
      <br />
      <p class="section__content">좌: 변경 전, 우: 변경 후</p>
      <div class="section__element--row">
        <img class="section__image" src={colorBefore1} alt="color before1" width="45%" />
        <img class="section__image" src={colorAfter1} alt="color after1" width="45%" />
      </div>
      <br />
      <div class="section__element--row">
        <img class="section__image" src={colorBefore2} alt="color before2" width="45%" />
        <img class="section__image" src={colorAfter2} alt="color after2" width="45%" />
      </div>
    </div>
  </section>
</div>

<style>
  .area {
    padding: 20px 0;
    background-color: var(--color-bg1);
  }

  .section {
    width: 100%;
    max-width: var(--max-width);
    margin: 0 auto;
    padding: 20px 16px;
  }

  .section__header {
    font-size: 26px;
    color: white;
  }

  .section__sub-header {
    font-size: 24px;
    color: white;
    margin-bottom: 20px;
  }

  .section__element {
    margin: 30px 0 50px;
  }

  .section__element--row {
    display: flex;
    gap: 20px;
  }

  .section__image {
    margin-top: 20px;
  }

  .section__content {
    color: white;
  }

  .section__content--strong {
    color: white;
    font-weight: 700;
    text-decoration: underline;
  }
</style>
