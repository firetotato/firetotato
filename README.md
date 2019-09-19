<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="UTF-8">
    <meta name="ixeb-studio:guide-vline" content="">
    <meta name="ixeb-studio:guide-hline" content="">
    <meta name="generator" content="iXebStudio Platform 2.2019.0808.5">
    <meta name="ixeb-studio:SaveZOrder" content="undefined">
    <meta name="ixeb-studio:grid-size" content="10x10">
    <meta name="ixeb-studio:screen-size" content="1280x1024">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="created" content="2019/09/10 14:17">
	<link href = "style.css" rel="stylesheet" type="text/css">
	<title>File title</title>
	<script type="text/javascript" src="../ixeb/ext/jquery/2.2.1/jquery-2.2.1.min.js"></script>
	<script type="text/javascript" src="../ixeb/lib/ixebBase.min.js"></script>
	<!-- From here, enter your script and style. -->
	<script type="text/javascript">
    /**
     * @작성자 : {USER}
     * @작성날짜 : 2019-09-17
     * @description : 컨트롤 영역에서 왼쪽 마우스 버튼을 클릭했을 때 발생하는 이벤트
     * @return 
     */
    function onclick_button1(e) {
        //TODO:
        
    }
    
    /**
     * @작성자 : {USER}
     * @작성날짜 : 2019-09-10
     * @description : 컨트롤 영역에서 왼쪽 마우스 버튼을 클릭했을 때 발생하는 이벤트
     * @return 
     */
    function onclick_button0(e) {
        //TODO:
        
    }
    
    </script>
    <style>
        .center{
            text-align: center;
        }
        table, th, td {
        border: 1px solid #bcbcbc;
        }
        .pull-left{
            float:left;
        }
        .tab-button-wrapper.selected{
            background-color: #fff;
        }
       
        .tabbuttons{
            background-color:white;
        }
        i-tabs .tabbuttons > div{
            background-color: #00a9b5;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div style="padding: 10px;border-bottom:2px solid black;">
            <h3 style="position:relative;left:0px;top:0px;height:16px">내부거래심의결과 통보서 상세</h3>
            <i-text text="> 나의 업무 > 관리자 메뉴 > 사용자 관리" style="position: absolute;height: 19px;width:232px;left:600px;top:10px" id="text0"></i-text>
            <i-text text="  > 내부거래심의 결과 통보서 상세" style="height: 19px;width: 232px;position:absolute;font-weight:bold;left:830px;top:10px" id="text1"></i-text>
            <i-button text="화면인쇄" style="width:69px;height:34px;position:absolute;left:1020px;top:0px" id="button0" onclick="onclick_button0(arguments[0])" tabIndex="1"></i-button>
        </div>
    </div>
    <div style="padding : 10px;">
        <p>본 검토의견에 대해 추가 협의가 필요한 경우 하단의[결재선지정] 후 [+재협의요청등록] 버튼을 클릭하여 작성해 주시기 바랍니다.</p>
    </div>
    <article>
        <div style = "background-color :beige; height :25px">
            <i-button class="common-type" text=" 결재선지정" id="btn_1" tabIndex="2"></i-button>
            <i-button class="common-type" text="임시저장" id="btn_2" tabIndex="3"></i-button>
            <i-button class="common-type" text="재협의요청등록" id="btn_3" tabIndex="4"></i-button>
            <i-button class="normal-type" text="결재요청" id="btn_4" tabIndex="5"></i-button>
            <i-button class="common-type" text="회람" id="btn_5" tabIndex="6"></i-button>
        </div>
    </article>
    <article>
        <i-group text="결재경로" class="line_type" bulletColor="#00a9b5"></i-group>
    </article>
    <article>
        <table style="text-align: center; border : 1px solid #bcbcbc; width : 100%">
            <tbody>
                <tr>
                    <th>요청부서</th>
                    <td>
                        <div class="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color : #00a9b5; color : white; padding 2px;">
                                <span>부산지사</span>
                            </div>
                            <div style = "padding 2px;">
                                <p>강상우/부장</p>
                                <p>결재요청 (2019-04-02)</p>
                            </div>
                        </div>
                        <div style = "padding 2px; margin-top : 15px;" class="pull-left">
                            <p> -> </p>     
                        </div>
                        <div class="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color : #00a9b5; color : white; padding 2px">
                                <span>부산지사</span>
                            </div>
                            <div>
                                <p>박광일/지사장</p>
                                <p>승인 (2019-04-02)</p>
                            </div>
                        </div>
                    </td>
                </tr>
                <tr>
                    <th>수신부서</th>
                    <td>
                        <div class="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color :#00a9b5; color : white; padding 2px;">
                                <p>법무팀</p>
                            </div>
                            <div>
                                <p>이승구/과장</p>
                                <p>결재요청 (2019-04-02)</p>
                            </div>
                        </div>
                        <div style = "padding 2px; margin-top : 15px;" class="pull-left">
                            <p> -> </p>
                        </div>
                        <div class="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color : #00a9b5; color : white; padding 2pz;">
                                <span>법무팀</span>
                            </div>
                            <div>
                                <p>박덕진/팀장</p>
                                <p>승인 (2019-04-02)</p>
                            </div>
                        </div>
                    </td>
                </tr>
                <tr>
                    <th>재협의</th>
                    <td>
                        <div class ="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color : #00a9b5; color : white; padding 2px;">
                             <span>부산지사</sapn>
                            </div>
                            <div>
                                <p>강상우/부장</p>
                                <p>결재요청 (2019-04-02)</p>
                                </div>
                        </div>    
                        <div style ="padding 2px; margin-top : 15px;" class="pull-left">
                            <p> -> </p>
                        </div>
                        <div class="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color : #00a9b5; color : white; padding 2px;">
                                <span>부산지사</span>
                            </div>
                            <div>
                                <p>박광일/지사장</p>
                                <p>승인 (2019-04-02)</p>
                            </div>
                        </div>
                        <div style="padding 2px; margin-top : 15px;" class="pull-left">    
                            <p> -> </p>
                        </div>
                        <div class="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color : #00a9b5; color : white; padding 2px;">
                                <span>법무팀</span>
                            </div>
                            <div>
                                <p>이승구/과장</p>
                                <p>결재요청 (2019-04-02)</p>
                            </div>
                        </div>
                        <div style="padding 2px; margin-top : 15px;" class="pull-left">
                            <p> -> </p>
                        </div>
                        <div class="pull-left" style="border : 1px solid grey;">
                            <div style = "background-color : #00a9b5; color : white; padding 2px;">
                                <span>법무팀</span>
                            </div>
                            <div>
                                <p>박덕진/팀장</p>
                                <p>승인 (2019-04-02)</p>
                            </div>
                        </div>
                    </td>
                </tr>
            </tbody>
        </table>
    </article>
    <i-tabs style="width:1140px" id="tabs0">
        <i-tabpage pagetitle="검토의견(0)">
            <p>0건의 검토의견이 있습니다.</p>
        </i-tabpage>
        <i-tabpage pagetitle="결재의견(0)">
            <p>0건의 결재의견이 있습니다.</p>
        </i-tabpage>
        <i-tabpage pagetitle="회람(0)">
            <p>0건의 회람이 있습니다.</p>
        </i-tabpage>
    </i-tabs>
    <article>
            <i-group text = "계약정보" class = "line_type" bulletColor="#00a9b5"></i-group>
    </article>
    <article>
        <table style = "border : 1px solid black;">
            <tbody style = "width: 100%">
                <div>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">문서번호</th>
                        <td>GSC-2019-C15674-A037</td>
                        <td style = "background-color: lightgoldenrodyellow; color: black;">진행상태</td>
                        <td>처리완료</td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">계약서 종류</th>
                        <td colspan="3">일반계약서(샘플 미제공)</td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">계약명</th>
                        <td colspan="3">계약검토 확인1</td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">계약대상업체</th>
                        <td colspan = "3">
                            <div class="pull-left" style="border : 1px ridge black; margin-right: 18px; margin-left: 2px">
                                <div style="text-align: center; background-color :lightgoldenrodyellow; color : black;">
                                    <p>구분</p>
                                </div>
                                <div>
                                    <p>법인사업자</p>
                                </div>
                            </div>
                            <div class="pull-left" style="border :1px ridge black; margin-right: 18px">
                                <div style="text-align: center; background-color :lightgoldenrodyellow; color : black;">
                                    <p>등록번호</p>
                                </div>
                                <div style="margin-bottom: 13px">
                                </div>
                            </div>
                            <div class="pull-left" style="border : 1px ridge black; margin-right : 2px">
                                <div style="text-align: center; background-color :lightgoldenrodyellow; color :black;">
                                    <p>고객/업체명</p>
                                </div>
                                <div>
                                    <p>************이</p>
                                </div>
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">내부거래심의여부</th>
                        <td colspan="3">해당 없음</td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">하도급심의여부</th>
                        <td colspan="3">해당 없음</td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">외환거래신고 등 해당여부</th>
                        <td colspan="3">해당 없음</td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color: black;">계약기간</th>
                        <td colspan="3">계약기간 없음</td>
                    </tr>
                    <tr>
                        <th style = "background-color: lightgoldenrodyellow; color : black;">검토요청계약서</th>
                        <td colspan="3">
                            <div style="padding : 10px 10px 10px 10px">
                                <p>첨부파일이 존재하지 않습니다.</p>
                            </div>
                        </td>
                    </tr>
                </div>
            </tbody>
        </table>
    </article>
    <article>
        <i-group text="검토요청정보" class="line_type" bulletColor="#00a9b5"></i-group>
    </article>
    <article>
        <div>
            <table style= "border : 1px solid black;">
                <tbody>
                    <tr>
                        <th style="background-color: lightgoldenrodyellow; color : black;">
                            <p>검토내용</p>
                            <p>(참고사항)</p>
                        </th>
                        <td colspan="3" style="position:relative;left:0px;top:0px"></td>
                    </tr>
                    <tr>
                        <th style="background-color: lightgoldenrodyellow; color : black;">참고첨부파일</th>
                        <td colspan="3">
                            <div style="background-color: lightgoldenrodyellow; color : black; margin: 5px 5px 5px 5px; border :1px solid white; ">
                                <p>(첨부파일이 존재하지 않습니다.)</p>
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <th style="background-color: lightgoldenrodyellow; color : black;">관련품의서</th>
                        <td colspan="3">
                            <div class="pull-left">
                                <div style="background-color: lightgoldenrodyellow; color : black;margin-bottom: 15px; padding-right: 100px;">
                                    <p>구분</p>
                                </div>
                            </div>
                            <div class="pull-left">
                                <div style="background-color: lightgoldenrodyellow;color : black;padding-right: 100px;position:relative;left:-0.0625px;top:0px;width:212px">
                                    <p>관련품의서</p>
                                </div>
                                <div>
                                    <p>(관련품의서가 존재하지 않습니다)</p>
                                </div>
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <th style="background-color: lightgoldenrodyellow; color:black;">관련계약정보</th>
                        <td colspan="3">
                            <div class="pull-left">
                                <div style="background-color: lightgoldenrodyellow; color : black; margin-bottom : 15px; padding-right: 100px;">
                                    <p>구분</p>
                                </div>
                            </div>
                            <div class="pull-left">
                                <div style="background-color: lightgoldenrodyellow;color : black; padding-right: 100px;">
                                     <p>관련계약명</p>
                                </div>
                                <div>
                                    <p>(관련계약정보가 존재하지 않습니다.)</p>
                                </div>
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <th style="background-color: lightgoldenrodyellow; color : black;">긴급검토여부</th>
                        <td colspan="3">
                            <p>일반</p>
                        </td>
                    </tr>
                    <tr>
                        <th style="background-color : lightgoldenrodyellow; color : black;">
                            <p>요청자</p>
                        </th>
                        <td>
                            <p>강상우 부장/부산지사</p>
                        </td>
                        <td style="background-color: lightgoldenrodyellow; color : black;">
                            <p>요청일시</p>
                        </td>
                        <td>
                            <div style="background-color: lightgoldenrodyellow; color : black; margin : 5px 5px 5px 5px; border : 1px solid white;">
                                <p>2019-04-02 15:00</p>
                            </div>
                        </td>
                    </tr>
                    <tr>
                        <th style="background-color: lightgoldenrodyellow; color : black;">관리담당자</th>
                        <td>
                            <p>강상우 부장/부산지사</p>
                        </td>
                        <td style="background-color: lightgoldenrodyellow; color : black;">
                            <p>요청일시</p>
                        </td>
                        <td>
                            <div style="background-color: lightgoldenrodyellow; color : black; margin : 5px 5px 5px 5px; border : 1px solid white;">
                                <p>2019-04-02 15:00</p>
                            </div>
                        </td>
                    </tr>
                </tbody>
            </div>
        </table>
    </article>
    <article>
        <div style="position:relative;left:0px;top:0px;height:40px">
            <i-button text="목록으로" style="position: absolute;width: 105px;top: 7px;left: 9px;height: 22px;background-color : #00a9b5;color : white;" id="button1" tabIndex="7"></i-button>
            <i-button text="보안문서 저장" style="position: absolute;top: 7px;left: 134px;width: 144px;height: 22px;background-color : #00a9b5;color : white;" id="button2" tabIndex="8"></i-button>
            <i-button text="계약검토요청서 작성(내용복사)" style="position: absolute;height: 21px;width: 180px;left: 599px;top: 7px;background-color: #00a9b5;color : white;" id="button3" tabIndex="9"></i-button>
            <i-button text="인장날인요청서 작성" style="position: absolute;width: 148px;height: 22px;left: 789px;top: 7px;background-color : #00a9b5;color : white;" id="button4" tabIndex="10"></i-button>
            <i-button text="전자서명요청서 작성" style="position: absolute;height: 22px;width: 149px;left: 949px;top: 7px;background-color : #00a9b5;color : white;" id="button5" tabIndex="11"></i-button>
        </div>
    </article>
</body>
</html>
