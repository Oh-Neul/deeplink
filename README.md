# App Scheme Test Page 11.31.0

<html>
  <head></head>
  <body>
    <table class="table table-striped">
    <thead>
    <tr>
        <th scope="col">구분</th>
        <th scope="col">경로</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>
            정렬, 필터 미적용 딥링크 진입시 UI
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./search/searchResult?searchResult_query=치킨&searchResult_serviceTab=DELIVERY">
              클릭
          </a>
        </td>
    </tr>
    <tr>
      <td>
          정렬, 필터 적용 딥링크 진입시 UI
      </td>
      <td>
          <a class="baeminScheme" href="baemin-beta://./search/searchResult?searchResult_query=치킨&searchResult_serviceTab=DELIVERY&searchResult_filters=%7b%22sorts%22%3a%5b%7b%22code%22%3a%22SORT__FAST%22%7d%5d%2c%22filters%22%3a%5b%7b%22type%22%3a%22MINIMUM_ORDER_PRICE%22%2c%22options%22%3a%5b%7b%22code%22%3a%22MINIMUM_ORDER_PRICE__LOWER_THAN_5000%22%7d%5d%7d%5d%2c%22toggleFilters%22%3a%5b%7b%22code%22%3a%22OTHER__SOLO%22%7d%2c%7b%22code%22%3a%22OTHER__BAEMIN_ONE%22%7d%5d%7d">
            클릭
        </a>
      </td>
    </tr>
    <tr>
      <td>
          정렬, 필터 적용 딥링크 진입시 Request 데이터 확인
      </td>
      <td>
          <a class="baeminScheme" href="baemin-beta://./search/searchResult?searchResult_query=치킨&searchResult_serviceTab=DELIVERY&searchResult_filters=%7b%22sorts%22%3a%5b%7b%22code%22%3a%22SORT__FAST%22%7d%5d%2c%22filters%22%3a%5b%7b%22type%22%3a%22MINIMUM_ORDER_PRICE%22%2c%22options%22%3a%5b%7b%22code%22%3a%22MINIMUM_ORDER_PRICE__LOWER_THAN_5000%22%7d%5d%7d%5d%2c%22toggleFilters%22%3a%5b%7b%22code%22%3a%22OTHER__SOLO%22%7d%2c%7b%22code%22%3a%22OTHER__BAEMIN_ONE%22%7d%5d%7d">
            클릭
        </a>
      </td>
    </tr>
    <tr>
        <td>
            정렬, 필터 적용 딥링크 진입 후 포장탭 선택시 API 호출 확인
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./search/searchResult?searchResult_query=치킨&searchResult_serviceTab=DELIVERY&searchResult_filters=%7b%22sorts%22%3a%5b%7b%22code%22%3a%22SORT__FAST%22%7d%5d%2c%22filters%22%3a%5b%7b%22type%22%3a%22MINIMUM_ORDER_PRICE%22%2c%22options%22%3a%5b%7b%22code%22%3a%22MINIMUM_ORDER_PRICE__LOWER_THAN_5000%22%7d%5d%7d%5d%2c%22toggleFilters%22%3a%5b%7b%22code%22%3a%22OTHER__SOLO%22%7d%2c%7b%22code%22%3a%22OTHER__BAEMIN_ONE%22%7d%5d%7d">
              클릭
          </a>
        </td>
    </tr>
    </tbody>
