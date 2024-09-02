# version 1.0.33
<br>sign(0)s_VerNic [생성시 Sign.Name("CheckYo")]
<br>sign(1)s_Letter == mList(1)AppName
<br>sign(2){s_Notice}s_Letter2 == mList(3)AppNotice [메인 메모]
<br>sign(3){s_URL_1}s_Ebmty2 == mList(51)UseURL_1
<br>sign(4){s_URL_2}s_URL == {mList(52)UseURL_2}(51)UseURL [광고 4슬롯 링크]
<br>sign(5){s_URL_3}s_Ebmty4 == mList(53)UseURL_3
<br>sign(6){s_URL_4}s_AdsNotice == {mList(54)UseURL_4}(4)AppLetter [업뎃 공지]
<br>sign(7){s_AdsLetter_1}s_AdsL1 == mList(12){AdsLetter_1}AdsL1 [광고 슬롯 설명]
<br>sign(8){s_AdsLetter_2}s_AdsL2 == mList(14){AdsLetter_2}AdsL2 [광고 슬롯 설명]
<br>sign(9){s_AdsLetter_3}s_AdsL3 == mList(16){AdsLetter_3}AdsL3 [광고 슬롯 설명]
<br>sign(10){s_AdsLetter_4}s_AdsL4 == mList(18){AdsLetter_4}AdsL4 [광고 슬롯 설명]
<br>sign(11){s_AdsLetter_1E}s_AdsL1E == mList(13){AdsLetter_1E}AdsL1E [광고 슬롯 설명]
<br>sign(12){s_AdsLetter_2E}s_AdsL2E == mList(15){AdsLetter_2E}AdsL2E [광고 슬롯 설명]
<br>sign(13){s_AdsLetter_3E}s_AdsL3E == mList(17){AdsLetter_3E}AdsL3E [광고 슬롯 설명]
<br>sign(14){s_AdsLetter_4E}s_AdsL4E == mList(19){AdsLetter_4E}AdsL4E [광고 슬롯 설명]
<br>**sign(15)s_webImage_1 == mList(4)AdsImage_1
<br>**sign(16)s_webImage_2 == mList(6)AdsImage_2
<br>**sign(17)s_webImage_3 == mList(8)AdsImage_3
<br>**sign(18)s_webImage_4 == mList(10)AdsImage_4
<br>**sign(19)s_webImage_1E == mList(5)AdsImage_1E
<br>**sign(20)s_webImage_2E == mList(7)AdsImage_2E
<br>**sign(21)s_webImage_3E == mList(9)AdsImage_3E
<br>**sign(22)s_webImage_4E == mList(11)AdsImage_4E
<br>
<br>xyz(0){f_AdsBlocScale}f_Estimate == mList(31)AdsBlocScale [공수 월 통합 배율]
<br>xyz(1)f_TransEstimate [공수 증감량]
<br>xyz(2){f_Estimate}f_empty [**공수 월 통합 배율]
<br>xyz(3){f_EnterEasyBt1_Value}f_CDA1_Value [이지버튼 고정 공수 값]
<br>xyz(4){f_EnterEasyBt2_Value}f_CDA2_Value [이지버튼 고정 공수 값]
<br>xyz(5){f_EnterEasyBt3_Value}f_CDA3_Value [이지버튼 고정 공수 값]
<br>xyz(6){f_EnterEasyBt4_Value}f_CDA4_Value [이지버튼 고정 공수 값]
<br>
<br>set(0)iS_Language [언어 설정]
<br>set(1)iS_Ver == Ver.Put([현재 앱버전])
<br>set(2){iS_AdsLayoutColor}iS_BackVer == mList(30)AdsLayoutColor
<br>set(3){null}iS_CDA1_Day [이지버튼 사용 일- 실 사용]
<br>set(4){null}iS_CDA2_Day [이지버튼 사용 일- 실 사용]
<br>set(5){null}iS_CDA3_Day [이지버튼 사용 일- 실 사용]
<br>set(6){null}iS_CDA4_Day [이지버튼 사용 일- 실 사용]
<br>set(7)iS_BoxFont [스케줄러 시박스 폰트 크기]
<br>set(8)iS_MemoFont
<br>set(9)iS_OtherFont
<br>set(10)iS_imSet_BackSCDB [배경색 설정]
<br>set(11)iS_imSet_BackLB [배경판 색 설정]
<br>set(12)iS_AdsS1 == {mList(32)AdsVerify_1}(31)AdsS1 [애드몹 광고 스위치 번호]
<br>set(13)iS_AdsS2 == {mList(33)AdsVerify_2}(32)AdsS2 [애드몹 광고 스위치 번호]
<br>set(14)iS_AdsS3 == {mList(34)AdsVerify_3}(33)AdsS3 [애드몹 광고 스위치 번호]
<br>set(15)iS_AdsS4 == {mList(35)AdsVerify_4}(34)AdsS4
<br>set(16){iS_AdsPrize_1}iS_AdsPrize == {mList(36)AdsPrize_1}(30)AdsPrize [4슬롯 보상 AP]
<br>set(17){iS_AdsPrize_2}iS_AutoAP == {mList(37)AdsPrize_2}(50)AutoAP [AP 자동 축적]
<br>set(18){iS_AdsPrize_3}iS_UseURL == mList(38)AdsPrize_3
<br>**set(19)iS_AdsPrize_4 == mList(39)AdsPrize_4
<br>**set(20)iS_AutoAP == mList(50)AutoAP
<br>
<br>memory(0)iM_Advertise [광고 포인트(AP)]
<br>memory(1)iM_Earn [일일 공수(일 단가)]
<br>memory(2)iM_Additional [추가 수입]
<br>memory(3)iM_Total [월 통합 금액]
<br>memory(4)iM_Period [월 계산 날짜]
<br>memory(5)iM_Attend [출근 일수]
<br>memory(6)iM_SaveYY [저장 연도]
<br>memory(7)iM_SaveMM [저장 월]
<br>memory(8)iM_SaveDD [저장 일]
<br>memory(9)iM_CertifyDay [커티피데이]
<br>memory(10){iM_EnterEasyBt1_Day}iM_CDA1_Day [이지버튼 사용 일- 복사]
<br>memory(11){iM_EnterEasyBt2_Day}iM_CDA2_Day [이지버튼 사용 일- 복사]
<br>memory(12){iM_EnterEasyBt3_Day}iM_CDA3_Day [이지버튼 사용 일- 복사]
<br>memory(13){iM_EnterEasyBt4_Day}iM_CDA4_Day [이지버튼 사용 일- 복사]
<br>
<br>onOff(0)b_HideE [일 단가 보기/가리기]
<br>onOff(1){b_HideA}b_HideT [통합 금액 보기/가리기]
<br>onOff(2){b_HideT}b_OnPeriod [월 계산 사용 여부]
<br>onOff(3){b_OnPeriod}b_HaveOld
<br>onOff(4)b_GetDay [턴 데이 세이브 파일 체크]
<br>onOff(5){b_questToday}b_AdsOpen == {not link}mList(21)AdsOpen [광고 4슬롯 사용 여부]
<br>onOff(6)b_AdsToday == {not link}mList(20)AdsTest [광고 4슬롯 일일 체크]
<br>onOff(7){b_TestApp}b_AdsTest == mList(20)TestApp [광고 4슬롯 설명/언어 선택]
<br>**onOff(8)b_adsTestID == mList(21)AdsRialID
<br>**onOff(9)b_adsBanner == mList(22)AdsBanner
<br>**onOff(10)b_OnMyAds_Slot1 == mList(23)OnMyAds_Slot1
<br>**onOff(11)b_OnMyAds_Slot2 == mList(24)OnMyAds_Slot2
<br>**onOff(12)b_OnMyAds_Slot3 == mList(25)OnMyAds_Slot3
<br>**onOff(13)b_OnMyAds_Slot4 == mList(26)OnMyAds_Slot4
<br><hr>
<br>(64), (63), (62), (61), (60)ListLimit,
<br>(59)ByteEmpty5, (58)ByteEmpty4, (57)ByteEmpty3, (56)ByteEmpty2, (55)ByteEmpty1,
<br>(49)Link_9, (48)Link_8, (47)Link_7, (46)Link_6, (45)Link_5,
<br>(44)Link_4, (43)Link_3, (42)Link_2, (41)Link_1, (40)Link_0,
<br>(29)OnEmpty3, (28)OnEmpty2, (27)OnEmpty1, (2)AppVersion, (0)AppNull
<br><hr>
<br>[ DataBase.cs - 1.0.33 ]
<br>5 => amo.RewardShow(),
<br>4 => {amo.RewaFVShow()}amo.RandomAdmob_R_RF(),
<br>3 => amo.FullViewShow(),
<br>2 => {amo.RandomAdmob_R_RF()}amo.RewaFVShow(),
<br>1 => amo.RandomAdmob_RF_FV(),
<br>_ => false,
<br><hr>
[ NColor ]
<br>ushot.MaxValue => NColor.BlurDeep,
<br>{110) Blur }
<br>{109) }{108) }{107) }{106) }{105) }
<br>{104) }{103) }{102) }{101) }{100) }
<br>{99) WhiteGray }{98) GrayWhite }{97) GrayRight }{96) GrayUp }{95) }
<br>{94) Gray }{93) }{92) GrayDark }{91) BlackUp }{90) }
<br>{89) GreenLimit }{88) GreenRight }{87) }{86) GreenUp }{85) GreenSimple }
<br>{84) Green }{83) GreenMix }{82) }{81) }{80) }
<br>{79) BlueLimit }{78) BlueSky }{77) BlueJean }{76) BlueUp }{75) }
<br>{74) Blue }{73) BlueMix }{72) }{71) }{70) }
<br>{69) RedLimit }{68) RedRight }{67) }{66) RedUp }{65) }
<br>{64) Red }{63) RedMix }{62) }{61) }{60) }
<br>{59) BrownUpSkin }{58) BrownSkin }{57) BrownDeepSkin }{56) BrownUp }{55) BrownSimple }
<br>{54) Brown }{53) BrownMix }{52) BrownDeep }{51) BrownDark }{50) BrownDeepDark }
<br>{49) YellowLimit }{48) YellowRight }{47) YellowJean }{46) YellowUp }{45) YellowSimple }
<br>{44) Yellow }{43) YellowMix }{42) YellowDeep }{41) }{40) }
<br>{39) PurpleLimit }{38) }{37) }{36) }{35) }
<br>{34) }{33) }{32) }{31) }{30) }
<br>{29) AquaLimit }{28) }{27) }{26) }{25) }
<br>{24) }{23) }{22) }{21) }{20) }
<br>{19) Luz_250 }{18) Luz_240 }{17) Luz_220 }{16) Luz_200 }{15) Luz_150 }
<br>{14) Luz_100 }{13) }{12) Luz_50 }{11) Luz_20 }{10) Luz_0 }
<br>{9) Placeholder }{8) }{7) }{6) }{5) }
<br>{4) }{3) }{2) White }{1) Black }{0) Clear }
<br><hr>
