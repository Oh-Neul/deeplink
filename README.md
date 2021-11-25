# App Scheme Test Page

<html>
  <head></head>
  <body>
    <table class="table table-striped">
    <thead>
    <tr>
        <th scope="col">경로</th>
        <th scope="col">App Scheme</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>
            베타 배민앱 메인화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home">baemin-beta://home</a>
        </td>
    </tr>
    <tr>
        <td>
            베타 배민앱 주소설정 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./locationSettings">baemin-beta://./locationSettings</a>
        </td>
    </tr>
    <tr>
        <td>
            베타 배민앱 큐레이션 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./curationShopList">baemin-beta://./curationShopList</a>
        </td>
    </tr>
    <tr>
        <td>
            운영 배민앱 큐레이션 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin://./curationShopList">baemin://./curationShopList</a>
        </td>
    </tr>
      <tr>
        <td>
            배민주문 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin://home/deliveryTracking?deliveryTracking_ordType=baemin">baemin</a>
        </td>
    </tr>
      <tr>
        <td>
            마켓 주문 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin://home/deliveryTracking?deliveryTracking_ordType=market">market</a>
        </td>
    </tr>
      <tr>
        <td>
            스토어 주문 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin://home/deliveryTracking?deliveryTracking_ordType=baeminStore">baeminStore</a>
        </td>
    </tr>
      <tr>
        <td>
            (상대경로)<br>
            열혈분식 방이점 가게 상세 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./shopDetail?shopDetail_shopNo=10663860">baemin-beta://./shopDetail?shopDetail_shopNo=10663860</a>
        </td>
    </tr>
      <tr>
        <td>
            (절대경로)<br>
            열혈분식 방이점 가게 상세 이동
        </td>
        <td>
<a class="baeminScheme" href="baemin-beta://home/shopDetail?shopDetail_shopNo=10663860">baemin-beta://home/shopDetail?shopDetail_shopNo=10663860</a><br>
            <a class="baeminScheme" href="baemin-beta://home/shopList/shopDetail?shopList_categoryCode=33&shopDetail_shopNo=10663860">baemin-beta://home/shopList/shopDetail?shopList_categoryCode=33&shopDetail_shopNo=10663860</a>
        </td>
      </tr>
      <tr>
        <td>
            배달현황
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./shopDetail/menuDetail?shopDetail_shopNo=13009755&menuDetail_shopNo=13009755&menuDetail_menuNo=32479007&menuDetail_categoryTypeCode=1">이동</a>
        </td>
    </tr>
      <tr>
        <td>
            장바구니 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./cart">장바구니</a>
        </td>
    </tr>
      <tr>
        <td>
            딥링크 메시지
        </td>
        <td>
            <a class="baeminScheme" href="baemin-action-beta://showToast?showToast_message=가나다라 메시지 Message 1234 !@#$">가나다라 Toast 메시지 Message 1234 !@#$</a>
        </td>
    </tr>
      
      
      
      
      
</table>
    
  </body>
</html>
