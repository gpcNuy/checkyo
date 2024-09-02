# Version 1.0.32
<br>sign(0)s_VerNic [생성시 Sign.Name("CheckYo")]
<br>sign(1)s_Letter
<br>sign(2)s_Letter2 [메인 메모]
<br>sign(3)s_Ebmty2
<br>sign(4)s_URL == mList(41)Link_1 [광고 4슬롯 링크]
<br>{db.mList[CheckYo.Link_0 + int.Parse(db.mList[CheckYo.UseURL])];}
<br>sign(5)s_Ebmty4
<br>sign(6)s_AdsNotice == mList(4)AppLetter [업뎃 공지]
<br>sign(7)s_AdsL1 == mList(12)AdsL1 [광고 슬롯 설명]
<br>sign(8)s_AdsL2 == mList(14)AdsL2 [광고 슬롯 설명]
<br>sign(9)s_AdsL3 == mList(16)AdsL3 [광고 슬롯 설명]
<br>sign(10)s_AdsL4 == mList(18)AdsL4 [광고 슬롯 설명]
<br>sign(11)s_AdsL1E == mList(13)AdsL1E [광고 슬롯 설명]
<br>sign(12)s_AdsL2E == mList(15)AdsL2E [광고 슬롯 설명]
<br>sign(13)s_AdsL3E == mList(17)AdsL3E [광고 슬롯 설명]
<br>sign(14)s_AdsL4E == mList(19)AdsL4E [광고 슬롯 설명]
<br>
<br>xyz(0)f_Estimate [공수 월 통합 배율]
<br>xyz(1)f_TransEstimate [공수 증감량]
<br>xyz(2)f_empty
<br>xyz(3)f_CDA1_Value [이지버튼 고정 공수 값]
<br>xyz(4)f_CDA2_Value [이지버튼 고정 공수 값]
<br>xyz(5)f_CDA3_Value [이지버튼 고정 공수 값]
<br>xyz(6)f_CDA4_Value [이지버튼 고정 공수 값]
<br>
<br>set(0)iS_Language [언어 설정]
<br>set(1)iS_Ver == Ver.Put([현재 앱버전])
<br>set(2)iS_BackVer
<br>set(3)iS_CDA1_Day [이지버튼 사용 일- 실 사용]
<br>set(4)iS_CDA2_Day [이지버튼 사용 일- 실 사용]
<br>set(5)iS_CDA3_Day [이지버튼 사용 일- 실 사용]
<br>set(6)iS_CDA4_Day [이지버튼 사용 일- 실 사용]
<br>set(7)iS_BoxFont [스케줄러 시박스 폰트 크기]
<br>set(8)iS_MemoFont
<br>set(9)iS_OtherFont
<br>set(10)iS_imSet_BackSCDB [배경색 설정]
<br>set(11)iS_imSet_BackLB [배경판 색 설정]
<br>set(12)iS_AdsS1 == mList(31)AdsS1 [애드몹 광고 스위치 번호]
<br>set(13)iS_AdsS2 == mList(32)AdsS2 [애드몹 광고 스위치 번호]
<br>set(14)iS_AdsS3 == mList(33)AdsS3 [애드몹 광고 스위치 번호]
<br>set(15)iS_AdsS4 == mList(34)AdsS4
<br>set(16)iS_AdsPrize == mList(30)AdsPrize [4슬롯 보상 AP]
<br>**set(17)iS_AutoAP == mList(50)AutoAP [AP 자동 축적]
<br>**set(18)iS_UseURL
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
<br>memory(10)iM_CDA1_Day [이지버튼 사용 일- 복사]
<br>memory(11)iM_CDA2_Day [이지버튼 사용 일- 복사]
<br>memory(12)iM_CDA3_Day [이지버튼 사용 일- 복사]
<br>memory(13)iM_CDA4_Day [이지버튼 사용 일- 복사]
<br>
<br>onOff(0)b_HideE [일 단가 보기/가리기]
<br>onOff(1)b_HideT [통합 금액 보기/가리기]
<br>onOff(2)b_OnPeriod [월 계산 사용 여부]
<br>onOff(3)b_HaveOld
<br>onOff(4)b_GetDay [턴 데이 세이브 파일 체크]
<br>onOff(5)b_AdsOpen == mList(21)AdsOpen [광고 4슬롯 사용 여부]
<br>onOff(6)b_AdsToday == **{mList(20)AdsTest} [광고 4슬롯 일일 체크]
<br>**onOff(7)b_AdsTest == [광고 4슬롯 설명/언어 선택]
<br><hr>
<br>mList(0)AppNull, mList(1)AppName, mList(2)AppVersion, mList(3)AppNotice, 
<br>mList(5)Empty2, mList(6)Empty3, mList(7)Empty4, mList(8)Empty5, 
<br>mList(9)Empty6, mList(10)Empty7, mList(11)Empty8, mList(22)OnEmpty2, mList(23)OnEmpty3, 
<br>mList(24)OnEmpty4, mList(25)OnEmpty5, mList(26)OnEmpty6, 
<br>mList(27)OnEmpty7, mList(28)OnEmpty8, mList(29)OnEmpty9,
<br>mList(35)Empty9, mList(36)Empty10, mList(37)Empty11, mList(38)Empty12, mList(39)Empty13, 
<br>mList(40)Link_0, mList(42)Link_2, mList(43)Link_3, mList(44)Link_4, 
<br>mList(45)Link_5, mList(46)Link_6, mList(47)Link_7, mList(48)Link_8, mList(49)Link_9,
<br>**mList(51)UseURL, **mList(52)ByteEmpty_2, **mList(53)ByteEmpty_3, **mList(54)ByteEmpty_4, 
<br>**mList(55)ByteEmpty_5, **mList(56)ByteEmpty_6, **mList(57)ByteEmpty_7, 
<br>**mList(58)ByteEmpty_8, **mList(59)ByteEmpty_9, **mList(60)ListLimit
<br><hr>
<br>[ DataBase.cs - 1.0.32 ]
<br>1 => amo.RandomAdmob_RF_FV(),
<br>4 => amo.RandomAdmob_R_RF(),
<br>3 => amo.FullViewShow(),
<br>2 => amo.RewaFVShow(),
<br>5 => amo.RewardShow(),
<br>_ => false,
<br><hr>
