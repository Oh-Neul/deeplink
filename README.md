<head>
    <meta charset=UTF-8"/>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
</head>

<body>


<h1>App Scheme Test Page</h1>

<br><br>

<div class="input-group mb-3">
    <div class="input-group-prepend">
        <label class="input-group-text" for="selectBeta">테스트 서버</label>
    </div>
    <select id="selectBeta">
        <option value="baemin-beta">베타</option>
        <option value="baemin">운영</option>
    </select>
</div>

<div class="input-group mb-3">
    <div class="input-group-prepend">
        <span class="input-group-text" id="basic-addon1">생성하려는 딥링크 입력</span>
    </div>
    <input type="text" id="createLink" name="link"><br><br>
    <button type="button" id="createButton" class="btn btn-secondary">생성하기</button>
</div>

<p><a href="" id = "makelink"></a></p>



<br><br>

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
            베타 배민앱 메인화면 이동
            (탭 지정=0)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home?tab=0">baemin-beta://home?tab=0</a>
        </td>
    </tr>
    <tr>
        <td>
            치킨 카테고리 가게목록 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./shopList?shopList_categoryCode=1&shopList_displayCategory=CHICKEN">baemin-beta://./shopList?shopList_categoryCode=1&shopList_displayCategory=CHICKEN</a>
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
            <a class="baeminScheme" href="baemin-beta://home/shopDetail?shopDetail_shopNo=10663860">baemin-beta://home/shopDetail?shopDetail_shopNo=10663860</a><br><br>
            <a class="baeminScheme" href="baemin-beta://home/shopList/shopDetail?shopList_categoryCode=33&shopDetail_shopNo=10663860">baemin-beta://home/shopList/shopDetail?shopList_categoryCode=33&shopDetail_shopNo=10663860</a>
        </td>
    </tr>
    <tr>
        <td>
            교촌치킨 프랜차이즈[2011100216] 상세 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/franchiseBrandDetail?franchiseBrandDetail_franchiseNo=2011100216&franchiseBrandDetail_tab=menu">baemin-beta://home/franchiseBrandDetail?franchiseBrandDetail_franchiseNo=2011100216&franchiseBrandDetail_tab=menu</a><br><br>
            <a class="baeminScheme" href="baemin-beta://home/franchiseBrandDetail?franchiseBrandDetail_franchiseNo=2011100216&franchiseBrandDetail_tab=shopList">baemin-beta://home/franchiseBrandDetail?franchiseBrandDetail_franchiseNo=2011100216&franchiseBrandDetail_tab=shopList</a>

        </td>
    </tr>
    <tr>
        <td>
            쿠폰함 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/couponbox">baemin-beta://home/couponbox</a>
        </td>
    </tr>
    <tr>
        <td>
            포인트함 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/pointbox">baemin-beta://home/pointbox</a>
        </td>
    </tr>
    <tr>
        <td>
            (메인화면에서)<br>
            내부 웹뷰(네이버) 띄우기
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/webview?webview_url=http%3A%2F%2Fnaver.com">baemin-beta://home/webview?webview_url=http%3A%2F%2Fnaver.com</a>
        </td>
    </tr>
    <tr>
        <td>
            (상대경로)<br>
            내부 웹뷰(네이버) 띄우기
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./webview?webview_url=http%3A%2F%2Fnaver.com&webview_type=full">baemin-beta://./webview?webview_url=http%3A%2F%2Fnaver.com&webview_type=full</a><br><br>
            <a class="baeminScheme" href="baemin-beta://./webview?webview_url=http%3A%2F%2Fnaver.com&webview_type=no_navigation">baemin-beta://./webview?webview_url=http%3A%2F%2Fnaver.com&webview_type=no_navigation</a>
        </td>
    </tr>
    <tr>
        <td>
            바로결제 내역 상세화면 이동<br>
            계정정보 : sjlim001@woowahan.com / 00000000 <br>
            (이 외 계정으로 접근 불가능 해야함<br>
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/orderHistoryDetail?orderHistoryDetail_orderNo=BLMWU00033">baemin-beta://home/orderHistoryDetail?orderHistoryDetail_orderNo=BLMWU00033</a>
        </td>
    </tr>
    <tr>
        <td>
            바로결제 내역 목록 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/orderHistory?orderHistory_type=baemin">baemin-beta://home/orderHistory?orderHistory_type=baemin</a>
        </td>
    </tr>
    <tr>
        <td>
            장바구니 화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./cart">baemin-beta://./cart</a>
        </td>
    </tr>
    <tr>
        <td>
            본인인증화면(웹뷰) 띄우기 (테스트 불가)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://authentication">baemin-beta://authentication</a>
        </td>
    </tr>
    <tr>
        <td>
            배민키친 화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/baeminKitchen">baemin-beta://home/baeminKitchen</a>
        </td>
    </tr>
    <tr>
        <td>
            환경설정 화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/settings">baemin-beta://home/settings</a>
        </td>
    </tr>
    <tr>
        <td>
            로그인 화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/login">baemin-beta://home/login</a>
        </td>
    </tr>
    <tr>
        <td>
            위치설정화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/locationSettings">baemin-beta://home/locationSettings</a>
        </td>
    </tr>
    <tr>
        <td>
            배민 라이더스 화면(한식) 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./eatoutShopList?eatoutShopList_themeCode=37&eatoutShopList_pageName=%EB%B0%B0%EB%AF%BC%EB%9D%BC%EC%9D%B4%EB%8D%94%EC%8A%A4&eatoutShopList_displayCategory=RIDERS_KOREAN">baemin-beta://./eatoutShopList?eatoutShopList_themeCode=37&eatoutShopList_pageName=배민라이더스&eatoutShopList_displayCategory=RIDERS_KOREAN</a>
        </td>
    </tr>
    <tr>
        <td>
            프랜차이즈목록 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/franchiseList">baemin-beta://home/franchiseList</a>
        </td>
    </tr>
    <tr>
        <td>
            맛집 더보기 화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/shopRankingList">baemin-beta://home/shopRankingList</a>
        </td>
    </tr>
    <tr>
        <td>
            배달현황 지면<br>
            (주문번호는 바꾸어 사용)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/deliveryTracking?deliveryTracking_orderNo=BHHPH03547&deliveryTracking_clearCart=true">baemin-beta://home/deliveryTracking?deliveryTracking_orderNo=BHHPH03547&deliveryTracking_clearCart=true</a>
        </td>
    </tr>
    <tr>
        <td>
            회원가입
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/login/signup">baemin-beta://home/login/signup</a>
        </td>
    </tr>
    <tr>
        <td>
            내정보수정
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./userInfoEdit">baemin-beta://./userInfoEdit</a>
        </td>
    </tr>
    <tr>
        <td>
            배민마켓가게 상세
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/market?market_shopNo=661817">baemin-beta://home/market?market_shopNo=661817</a>
        </td>
    </tr>
    <tr>
        <td>
            배민마켓 메뉴 상세<br>
            (Android)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./marketMenu?marketMenu_shopNo=661702&marketMenu_menuNo=1387510">baemin-beta://./marketMenu?marketMenu_shopNo=661702&marketMenu_menuNo=1387510</a>
        </td>
    </tr>
    <tr>
        <td>
            배민마켓 메뉴 상세<br>
            (iOS)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/market/marketMenu?market_shopNo=661702&marketMenu_shopNo=661702&marketMenu_menuNo=1387510">baemin-beta://home/market/marketMenu?market_shopNo=661702&marketMenu_shopNo=661702&marketMenu_menuNo=1387510</a>
        </td>
    </tr>
    <tr>
        <td>
            검색시 배민마켓 가게상세<br>
            (iOS)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://market?market_shopNo=661817&market_themeCode=64">baemin-beta://market?market_shopNo=661817&market_themeCode=64</a>
        </td>
    </tr>
    <tr>
        <td>
            "도미노" 검색결과 화면<br>
            (iOS)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./search?search_query=%EB%8F%84%EB%AF%B8%EB%85%B8">baemin-beta://./search?search_query=%EB%8F%84%EB%AF%B8%EB%85%B8</a>
        </td>
    </tr>
    <tr>
        <td>
            "도미노" 검색결과 화면<br>
            (Android)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/search?search_query=%EB%8F%84%EB%AF%B8%EB%85%B8">baemin-beta://home/search?search_query=%EB%8F%84%EB%AF%B8%EB%85%B8</a>
        </td>
    </tr>
    <tr>
        <td>
            "피자" 검색결과 화면<br>
            (iOS)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./search?search_query=%ED%94%BC%EC%9E%90">baemin-beta://./search?search_query=%ED%94%BC%EC%9E%90</a>
        </td>
    </tr>
    <tr>
        <td>
            "피자" 검색결과 화면<br>
            (AOS)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/search?search_query=%ED%94%BC%EC%9E%90">baemin-beta://home/search?search_query=%ED%94%BC%EC%9E%90</a>
        </td>
    </tr>
    <tr>
        <td>
            큐레이션 더보기<br>
            미세먼지
        </td>
        <td>
            <a class="baeminScheme" href="baemin://./curationShopList?id=9742">baemin://./curationShopList?id=9742</a>
        </td>
    </tr>
    <tr>
        <td>
            큐레이션 더보기
            비유효<br>
        </td>
        <td>
            <a class="baeminScheme" href="baemin://./curationShopList?id=0000">baemin://./curationShopList?id=0000</a>
        </td>
    </tr>
    <tr>
        <td>
            (상대경로)<br>
            리뷰쓰기 화면 이동
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://home/reviewWrite?reviewWrite_shopNo=10662682&reviewWrite_memberId=sdV6FbukoS&reviewWrite_orderNo=B0EE00000E&reviewWrite_landingPage=shopDetail">baemin-beta://home/reviewWrite?reviewWrite_shopNo=10662682&reviewWrite_memberId=sdV6FbukoS&reviewWrite_orderNo=B0EE00000E&reviewWrite_landingPage=shopDetail</a>
        </td>
    </tr>
    <tr>
        <td>
            1인분<br>
            (아시안양식)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./soloShopList?soloShopList_displayCategoryCode=SOLO_WESTERN">baemin-beta://./soloShopList?soloShopList_displayCategoryCode=SOLO_WESTERN</a>
        </td>
    </tr>
    <tr>
        <td>
            상품권 등록
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./giftcard?giftcard_no=AAAAOOOOWWWW">baemin-beta://./giftcard?giftcard_no=AAAAOOOOWWWW</a>
        </td>
    </tr>
    <tr>
        <td>
            응답형가게목록<br>
            (1인분)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./responsiveShopList?
responsiveShopList_displayGroup=SOLO&responsiveShopList_title=1%EC%9D%B8%EB%B6%84&responsiveShopList_displayCategoryCode=SOLO_ALL">baemin-beta://./responsiveShopList?
                responsiveShopList_displayGroup=SOLO&responsiveShopList_title=1%EC%9D%B8%EB%B6%84&responsiveShopList_displayCategoryCode=SOLO_ALL</a>
        </td>
    </tr>
    <tr>
        <td>
            응답형가게목록<br>
            (번쩍배달)
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./responsiveShopList?
responsiveShopList_displayGroup=FASTEST&responsiveShopList_title=%EB%B2%88%EC%A9%8D%EB%B0%B0%EB%8B%AC&responsiveShopList_displayCategoryCode=FASTEST_ALL">baemin-beta://./responsiveShopList?
                responsiveShopList_displayGroup=FASTEST&responsiveShopList_title=%EB%B2%88%EC%A9%8D%EB%B0%B0%EB%8B%AC&responsiveShopList_displayCategoryCode=FASTEST_ALL</a>
        </td>
    </tr>
    <tr>
        <td>
            뭐먹지
        </td>
        <td>
            <a class="baeminScheme" href="baemin-beta://./eatCast">baemin-beta://./eatCast</a>
        </td>
    </tr>
    </tbody>
</table>
</body>


<script>
    $( "#createButton" ).click(function() {
        var linkName = $("#createLink").val();
        $( "#makelink" ).text(linkName);
        $( "#makelink" ).attr("href", linkName);
    });

    $( "#selectBeta" ).change(function() {
        var selectedValue = $("#selectBeta option:selected").val();
        console.log($(".baeminScheme"));

        if (selectedValue == "baemin") {
            $.each($(".baeminScheme"), function (index) {
                var firstLink = $(this).attr("href");
                var secondLink = firstLink.replace("baemin-beta", selectedValue);
                $(this).attr("href", secondLink);
                $(this).text(secondLink);

            });
        } else {
            $.each($(".baeminScheme"), function (index) {
                var firstLink = $(this).attr("href");
                var secondLink = firstLink.replace("baemin", selectedValue);
                $(this).attr("href", secondLink);
                $(this).text(secondLink);
            });
        }
    });


</script>
