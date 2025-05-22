# version 1.0.35
<br>sign(0)s_VerNic [생성시 Sign.AppName("CheckYo")]
<br>sign(1)s_Letter == mList(1)AppName [사용 보류]
<br>sign(2){s_Notice}s_Letter2 == mList(3)AppNotice [메인 메모=>업뎃 공지]
<br>sign(3){s_URL_1}s_Ebmty2 == mList(51)UseURL_1 [광고 1슬롯 링크]
<br>sign(4){s_URL_2}s_URL == {mList(52)UseURL_2}(51)UseURL [광고 4슬롯 링크=>광고 2슬롯 링크]
<br>sign(5){s_URL_3}s_Ebmty4 == mList(53)UseURL_3 [광고 3슬롯 링크]
<br>sign(6){s_URL_4}s_AdsNotice == {mList(54)UseURL_4}(4)AppLetter [업뎃 공지=>광고 4슬롯 링크]
<br>sign(7){s_AdsLetter_1}s_AdsL1 == mList(12){AdsLetter_1}AdsL1 [**광고 슬롯 설명]
<br>sign(8){s_AdsLetter_2}s_AdsL2 == mList(14){AdsLetter_2}AdsL2 [**광고 슬롯 설명]
<br>sign(9){s_AdsLetter_3}s_AdsL3 == mList(16){AdsLetter_3}AdsL3 [**광고 슬롯 설명]
<br>sign(10){s_AdsLetter_4}s_AdsL4 == mList(18){AdsLetter_4}AdsL4 [**광고 슬롯 설명]
<br>sign(11){s_AdsLetter_1E}s_AdsL1E == mList(13){AdsLetter_1E}AdsL1E [**광고 슬롯 설명]
<br>sign(12){s_AdsLetter_2E}s_AdsL2E == mList(15){AdsLetter_2E}AdsL2E [**광고 슬롯 설명]
<br>sign(13){s_AdsLetter_3E}s_AdsL3E == mList(17){AdsLetter_3E}AdsL3E [**광고 슬롯 설명]
<br>sign(14){s_AdsLetter_4E}s_AdsL4E == mList(19){AdsLetter_4E}AdsL4E [**광고 슬롯 설명]
<br>**sign(15)s_WebImage_1 == mList(4)AdsImage_1 [광고1 슬롯 한글판 이미지 변환]
<br>**sign(16)s_WebImage_2 == mList(6)AdsImage_2 [광고2 슬롯 한글판 이미지 변환]
<br>**sign(17)s_WebImage_3 == mList(8)AdsImage_3 [광고3 슬롯 한글판 이미지 변환]
<br>**sign(18)s_WebImage_4 == mList(10)AdsImage_4 [광고4 슬롯 한글판 이미지 변환]
<br>**sign(19)s_WebImage_1E == mList(5)AdsImage_1E [광고1 슬롯 영문판 이미지 변환]
<br>**sign(20)s_WebImage_2E == mList(7)AdsImage_2E [광고2 슬롯 영문판 이미지 변환]
<br>**sign(21)s_WebImage_3E == mList(9)AdsImage_3E [광고3 슬롯 영문판 이미지 변환]
<br>**sign(22)s_WebImage_4E == mList(11)AdsImage_4E [광고4 슬롯 영문판 이미지 변환]
<br>**sign(23)(24)(25)(26)(27)(28)(29)
<br>**sign(30)~(57)s_Memo10 ~ s_Memo45 [메모판 메모]
<br>
<br>xyz(0){f_AdsBlocScale}f_Estimate == mList(31)AdsBlocScale [공수 월 통합 배율=>배너 공간 크기]
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
<br>set(3){iS_Empty_1}iS_CDA1_Day [이지버튼 사용 일- 실 사용=>미사용]
<br>set(4){iS_Empty_2}iS_CDA2_Day [이지버튼 사용 일- 실 사용=>미사용]
<br>set(5){iS_Empty_3}iS_CDA3_Day [이지버튼 사용 일- 실 사용=>미사용]
<br>set(6){iS_Empty_4}iS_CDA4_Day [이지버튼 사용 일- 실 사용=>미사용]
<br>set(7)iS_BoxFont [스케줄러 시박스 폰트 크기]
<br>set(8)iS_MemoFont
<br>set(9)iS_OtherFont
<br>set(10)iS_ImSet_BackSCDB [배경색 설정]
<br>set(11)iS_ImSet_BackLB [배경판 색 설정]
<br>set(12){iS_AdsVerify_1}iS_AdsS1 == {mList(32)AdsVerify_1}(31)AdsS1 [애드몹 광고 스위치 번호]
<br>set(13){iS_AdsVerify_2}iS_AdsS2 == {mList(33)AdsVerify_2}(32)AdsS2 [애드몹 광고 스위치 번호]
<br>set(14){iS_AdsVerify_3}iS_AdsS3 == {mList(34)AdsVerify_3}(33)AdsS3 [애드몹 광고 스위치 번호]
<br>set(15){iS_AdsVerify_4}iS_AdsS4 == {mList(35)AdsVerify_4}(34)AdsS4 [애드몹 광고 스위치 번호]
<br>set(16){iS_AdsPrize_1}iS_AdsPrize == {mList(36)AdsPrize_1}(30)AdsPrize [4슬롯 보상 AP=>1슬롯 보상 AP]
<br>set(17){iS_AdsPrize_2}iS_AutoAP == {mList(37)AdsPrize_2}(50)AutoAP [AP 자동 축적=>2슬롯 보상 AP]
<br>set(18){iS_AdsPrize_3}iS_UseURL == mList(38)AdsPrize_3 [미사용=>3슬롯 보상 AP]
<br>**set(19)iS_AdsPrize_4 == mList(39)AdsPrize_4 [4슬롯 보상 AP]
<br>**set(20)iS_AutoAP == mList(50)AutoAP [AP 자동 축적]
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
<br>memory(10){iM_EnterEasyBt1_Day}iM_CDA1_Day [이지버튼 사용 일- 복사=>실 사용]
<br>memory(11){iM_EnterEasyBt2_Day}iM_CDA2_Day [이지버튼 사용 일- 복사=>실 사용]
<br>memory(12){iM_EnterEasyBt3_Day}iM_CDA3_Day [이지버튼 사용 일- 복사=>실 사용]
<br>memory(13){iM_EnterEasyBt4_Day}iM_CDA4_Day [이지버튼 사용 일- 복사=>실 사용]
<br>memory(14)iM_NoteSlot2 [노트패드 2슬롯 사용 기간]
<br>memory(15)iM_NoteSlot3 [노트패드 3슬롯 사용 기간]
<br>memory(16)iM_NoteSlot4 [노트패드 4슬롯 사용 기간]
<br>
<br>onOff(0)b_HideE [일 단가 보기/가리기]
<br>onOff(1){b_HideA}b_HideT [통합 금액 보기/가리기]
<br>onOff(2){b_HideT}b_OnPeriod [월 계산 사용 여부]
<br>onOff(3){b_OnPeriod}b_HaveOld
<br>onOff(4)b_GetDay [턴 데이 세이브 파일 체크]
<br>onOff(5){b_QuestToday}b_AdsOpen == {not link}mList(21)AdsOpen [광고 4슬롯 사용 여부=>미확정]
<br>onOff(6)b_AdsToday == {not link}mList(20)AdsTest [광고 4슬롯 일일 체크]
<br>onOff(7){b_TestApp}b_AdsTest == **mList(20)TestApp [광고 4슬롯 설명/언어 선택=>테스트앱]
<br>**onOff(8)b_AdsTestID == mList(21)AdsTestID [애드몹 리얼광고 여부]
<br>**onOff(9)b_AdsBanner == mList(22)AdsBanner [배너 사용 여부]
<br>**onOff(10)b_OnMyAds_Slot1 == mList(23)OnMyAds_Slot1 [광고1 자체 링크 사용 여부]
<br>**onOff(11)b_OnMyAds_Slot2 == mList(24)OnMyAds_Slot2 [광고2 자체 링크 사용 여부]
<br>**onOff(12)b_OnMyAds_Slot3 == mList(25)OnMyAds_Slot3 [광고3 자체 링크 사용 여부]
<br>**onOff(13)b_OnMyAds_Slot4 == mList(26)OnMyAds_Slot4 [광고4 자체 링크 사용 여부]
<br><hr>
<br>[ CheckYo ]
<br>(62-60)ListLimit
<br>(61-59)ByteEmpty5  (60-58)ByteEmpty4  (59-57)ByteEmpty3  (58-56)ByteEmpty2  (57-55)ByteEmpty1
<br>(56-54)UseURL_4 =s_6 (55-53)UseURL_3 =s_5 (54-52)UseURL_2 =s_4 (53-51)UseURL_1 =s_3 (52-50)AutoAP =iS_20
<br>(51-49)Link_9  (50-48)Link_8  (49-47)Link_7  (48-46)Link_6  (47-45)Link_5
<br>(46-44)Link_4  (45-43)Link_3  (44-42)Link_2  (43-41)Link_1  (42-40)Link_0
<br>(41-39)AdsPrize_4 =iS_19 (40-38)AdsPrize_3 =iS_18 (39-37)AdsPrize_2 =iS_17 (38-36)AdsPrize_1 =iS_16
<br>(37-35)AdsVerify_4 =iS_15 (36-34)AdsVerify_3 =iS_14 (35-33)AdsVerify_2 =iS_13 (34-32)AdsVerify_1 =iS_12
<br>(33-31)AdsBlocScale =f_0 (32-30)AdsLayoutColor =iS_2 (31-29)OnEmpty3  (30-28)OnEmpty2  (29-27)OnEmpty1
<br>(28-26)OnMyAds_Slot4 =b_13 (27-25)OnMyAds_Slot3 =b_12 (26-24)OnMyAds_Slot2 =b_11 (25-23)OnMyAds_Slot1 =b_10
<br>(24-22)AdsBanner =b_9 (23-21)AdsTestID =b_8 (22-20)TestApp =b_7
<br>(21-19)AdsLetter_4E =s_14 (20-18)AdsLetter_4 =s_10 (19-17)AdsLetter_3E =s_13 (18-16)AdsLetter_3 =s_9
<br>(17-15)AdsLetter_2E =s_12 (16-14)AdsLetter_2 =s_8 (15-13)AdsLetter_1E =s_11 (14-12)AdsLetter_1 =s_7
<br>(13-11)AdsImage_4E =s_22 (12-10)AdsImage_4 =s_18 (11-9)AdsImage_3E =s_21 (10-8)AdsImage_3 =s_17
<br>(9-7)AdsImage_2E =s_20 (8-6)AdsImage_2 =s_16 (7-5)AdsImage_1E =s_19 (6-4)AdsImage_1 =s_15
<br>(4-3)AppNotice =s_2 (3-2)AppVersion =needUpdate (2-1)AppName =s_1 (1-0)AppNull
<br><hr>
<br>[ DataBase.cs - 1.0.35 ]
<br>5 => amo.RewardShow(),
<br>4 => amo.RewaFVShow() {amo.RandomAdmob_R_RF()},
<br>3 => amo.FullViewShow(),
<br>2 => amo.RandomAdmob_R_RF() {amo.RewaFVShow()},
<br>1 => amo.RandomAdmob_RF_FV(),
<br>_ => false,
<br><hr>
<br>[ NColor ]
<br>ushot.MaxValue => NColor.BlurDeep,
<br>{65109) }{65108) }{65107) }{65106) }{65105) }
<br>{65104) }{65103) }{65102) }{65101) }{65100) }
<br>{195) Gray_Luz }{185) Green_Luz }{175) Blue_Luz }{165) Red_Luz }{155) Brown_Luz }
<br>{145) Yellow_Luz }{135) Purple_Luz }{125) Aqua_Luz }{115) Black_Luz }
<br>{110) Blur }
<br>{99) WhiteGray }{98) GrayWhite }{97) GrayRight }{96) GrayUp }{95) }
<br>{94) Gray }{93) }{92) GrayDark }{91) BlackUp }{90) }
<br>{89) GreenLimit }{88) GreenRight }{87) GreenUp }{86) GreenSmog }{85) GreenSimple }
<br>{84) Green }{83) GreenMix }{82) GreenWood }{81) GreenJungle }{80) GreenDeepDark }
<br>{79) BlueLimit }{78) BlueSky }{77) BlueJean }{76) BlueUp }{75) BlueSea }
<br>{74) Blue }{73) BlueMix }{72) BlueNight }{71) BlueDeep }{70) BlueDeepDark }
<br>{69) RedLimit }{68) RedRight }{67) RedUp }{66) RedSkin }{65) RedMix }
<br>{64) Red }{63) RedTomato }{62) RedJean }{61) RedBlood }{60) RedDeepDark }
<br>{59) BrownUpSkin }{58) BrownSkin }{57) BrownDeepSkin }{56) BrownUp }{55) BrownSimple }
<br>{54) Brown }{53) BrownMix }{52) BrownDeep }{51) BrownDark }{50) BrownDeepDark }
<br>{49) YellowLimit }{48) YellowRight }{47) Yellow }{46) YellowUp }{45) YellowSimple }
<br>{44) YellowJean }{43) YellowMix }{42) YellowGold }{41) YellowDeep }{40) YellowDeepDark }
<br>{39) PurpleLimit }{38) }{37) }{36) }{35) Purple }
<br>{34) }{33) }{32) }{31) PurpleDeep }{30) }
<br>{29) AquaLimit }{28) }{27) }{26) }{25) Aqua }
<br>{24) }{23) }{22) }{21) AquaDeep }{20) }
<br>{19) Luz_250 }{18) Luz_240 }{17) Luz_220 }{16) Luz_200 }{15) Luz_150 }
<br>{14) Luz_100 }{13) }{12) Luz_50 }{11) Luz_20 }{10) Luz_0 }
<br>{9) Placeholder }{8) }{7) }{6) }{5) }
<br>{4) }{3) }{2) White }{1) Black }{0) Clear }
<br><hr>
