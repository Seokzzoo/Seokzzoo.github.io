# Seokzzoo.github.io
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Pray For Bono</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  </head>
  <body>
    <h1 class="display-1" style="font-size: 500; font-weight: bold; text-align: center; font-style: italic; color: red;">WE LOVE BONO!</h1>
    <div id="carouselExample" class="carousel slide">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="JFF/BONOBONO.png" class="d-block w-100" alt="BONO">
        </div>
        <div class="carousel-item">
          <img src="JFF/Sad_Bono.png" class="d-block w-100" alt="SADBONO1">
        </div>
        <div class="carousel-item">
          <img src="JFF/Sad_Bono2.png" class="d-block w-100" alt="SADBONO2">
        </div>
        <div class="carousel-item">
          <img src="JFF/Sad_Bono3.png" class="d-block w-100" alt="SADBONO2">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <br><br><br>
    <div class="ct" style="display: flex;">
    <!-- Cards -->
      <div class="card" style="width: 18rem; ">
        <img src="JFF/BONOBONO.png" class="card-img-top" alt="BONO" title="BONO">
        <div class="card-body">
          <h5 class="card-title">보노보노</h5>
          <p class="card-text">안녕 나는 보노보노야<br>배고픈 나를 위해 후원해줘<br>월마다 만원만 내라</p>
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">후원</button>
        </div>
      </div>

      <!-- Modal -->
      <!-- 1. Modal id 속성 값과 각 버튼의 data-bs-target 속성 값이 각각 올바르게 일치하는지 확인 -->
      <!-- 2. Modal 버튼과 Modal 본체가 함께 다닐 필요 없다. -->
      <!-- 3. Modal 본체는 버튼을 눌러야만 활성화되는 코드이기 때문에 코드 최하단에 모아두는 것을 권장 -->
      <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h1 class="modal-title fs-5" id="exampleModalLabel">납치 완료</h1>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
              백만원이 입금되었습니다. 너 납치된거야 ^^
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">수</button>
              <button type="button" class="btn btn-primary">고</button>
            </div>
          </div>
        </div>
      </div>
      <table class="table" style="font-style:normal; font-weight: bold;">
        <thead>
          <tr>
            <th scope="col">후원 순위</th>
            <th scope="col">이름</th>
            <th scope="col">금액</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1등</th>
            <td>건</td>
            <td>50,000원</td>
          </tr>
          <tr>
            <th scope="row">2등</th>
            <td>보형</td>
            <td>30,000원</td>
          </tr>
          <tr>
            <th scope="row">3등</th>
            <td>석주</td>
            <td>10,000원</td>
          </tr>
        </tbody>
      </table>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
