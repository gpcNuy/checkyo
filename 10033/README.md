# version 1.0.33
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
<br>set(17)iS_AutoAP == mList(50)AutoAP [AP 자동 축적]
<br>set(18)iS_UseURL
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
<br>onOff(6)b_AdsToday == mList(20)AdsTest [광고 4슬롯 일일 체크]
<br>onOff(7)b_AdsTest == [광고 4슬롯 설명/언어 선택]
<br><hr>
<br>mList(0)AppNull, mList(1)AppName, mList(2)AppVersion, mList(3)AppNotice, 
<br>mList(5)Empty2, mList(6)Empty3, mList(7)Empty4, mList(8)Empty5, 
<br>mList(9)Empty6, mList(10)Empty7, mList(11)Empty8, mList(22)OnEmpty2, mList(23)OnEmpty3, 
<br>mList(24)OnEmpty4, mList(25)OnEmpty5, mList(26)OnEmpty6, 
<br>mList(27)OnEmpty7, mList(28)OnEmpty8, mList(29)OnEmpty9,
<br>mList(35)Empty9, mList(36)Empty10, mList(37)Empty11, mList(38)Empty12, mList(39)Empty13, 
<br>mList(40)Link_0, mList(42)Link_2, mList(43)Link_3, mList(44)Link_4, 
<br>mList(45)Link_5, mList(46)Link_6, mList(47)Link_7, mList(48)Link_8, mList(49)Link_9,
<br>*mList(51)UseURL, *mList(52)ByteEmpty_2, *mList(53)ByteEmpty_3, *mList(54)ByteEmpty_4, 
<br>*mList(55)ByteEmpty_5, *mList(56)ByteEmpty_6, *mList(57)ByteEmpty_7, 
<br>*mList(58)ByteEmpty_8, *mList(59)ByteEmpty_9, *mList(60)ListLimit
<br><hr>
<br>[ DataBase.cs - 1.0.32 ]
<br>1 => amo.RandomAdmob_RF_FV(),
<br>4 => amo.RandomAdmob_R_RF(),
<br>3 => amo.FullViewShow(),
<br>2 => amo.RewaFVShow(),
<br>5 => amo.RewardShow(),
<br>_ => false,
<br><hr>


[ CheckYo - in Sign.cs ] (99), (99), (99), (99), (99),
<br>
<br>(64), (63), (62), (61), (60)ListLimit,
<br>(59)ByteEmpty5, (58)ByteEmpty4, (57)ByteEmpty3, (56)ByteEmpty2, (55)ByteEmpty1,
<br>(54)UseURL_4, (53)UseURL_3, (52)UseURL_2, (51)UseURL_1, (50)AutoAP,
<br>(49)Link_9, (48)Link_8, (47)Link_7, (46)Link_6, (45)Link_5,
<br>(44)Link_4, (43)Link_3, (42)Link_2, (41)Link_1, (40)Link_0,
<br>(39)AdsPrize_4, (38)AdsPrize_3, (37)AdsPrize_2, (36)AdsPrize_1, (35)AdsVerify_4,
<br>(34)AdsVerify_3, (33)AdsVerify_2, (32)AdsVerify_1, (31)AdsBlocScale, (30)AdsLayoutColor,
<br>(29)OnEmpty3, (28)OnEmpty2, (27)OnEmpty1, (26)OnMyAds_Slot4, (25)OnMyAds_Slot3,
<br>(24)OnMyAds_Slot2, (23)OnMyAds_Slot1, (22)AdsBanner, (21)AdsRialID, (20)TestApp,
<br>(19)AdsLetter_4E, (18)AdsLetter_4, (17)AdsLetter_3E, (16)AdsLetter_3, (15)AdsLetter_2E,
<br>(14)AdsLetter_2, (13)AdsLetter_1E, (12)AdsLetter_1, (11)AdsImage_4E, (10)AdsImage_4,
<br>(9)AdsImage_3E, (8)AdsImage_3, (7)AdsImage_2E, (6)AdsImage_2, (5)AdsImage_1E,
<br>(4)AdsImage_1, (3)AppNotice, (2)AppVersion, (1)AppName, (0)AppNull,
<br><hr>
[ SFLt - const int ] (99), (99), (99), (99), (99),
<br>
<br>(24), (23), (22)s_webImage_4E, (21)s_webImage_3E, (20)s_webImage_2E,
<br>(19)s_webImage_1E, (18)s_webImage_4, (17)s_webImage_3, (16)s_webImage_2, (15)s_webImage_1,
<br>(14)s_AdsLetter_4E, (13)s_AdsLetter_3E, (12)s_AdsLetter_2E, (11)s_AdsLetter_1E, (10)s_AdsLetter_4,
<br>(9)s_AdsLetter_3, (8)s_AdsLetter_2, (7)s_AdsLetter_1, (6)s_URL_4, (5)s_URL_3,
<br>(4)s_URL_2, (3)s_URL_1, (2)s_Notice, (1)s_Letter, (0)s_VerNic,
<br>
<br>(9), (8), (7), (6)f_EnterEasyBt4_Value, (5)f_EnterEasyBt3_Value,
<br>(4)f_EnterEasyBt2_Value, (3)f_EnterEasyBt1_Value, (2)f_Estimate, (1)f_TransEstimate, (0)f_AdsBlocScale,
<br>
<br>(24), (23), (22), (21), (20)iS_AutoAP,
<br>(19)iS_AdsPrize_4, (18)iS_AdsPrize_3, (17)iS_AdsPrize_2, (16)iS_AdsPrize_1, (15)iS_AdsS4,
<br>(14)iS_AdsS3, (13)iS_AdsS2, (12)iS_AdsS1, (11)iS_imSet_BackLB, (10)iS_imSet_BackSCDB,
<br>(9)iS_OtherFont, (8)iS_MemoFont, (7)iS_BoxFont, (6)iS_Empty_4, (5)iS_Empty_3,
<br>(4)iS_Empty_2, (3)iS_Empty_1, (2)iS_AdsLayoutColor, (1)iS_Ver, (0)iS_Language,
<br>
<br>(14), (13)iM_EnterEasyBt4_Day, (12)iM_EnterEasyBt3_Day, (11)iM_EnterEasyBt2_Day, (10)iM_EnterEasyBt1_Day,
<br>(9)iM_CertifyDay, (8)iM_SaveDD, (7)iM_SaveMM, (6)iM_SaveYY, (5)iM_Attend,
<br>(4)iM_Period, (3)iM_Total, (2)iM_Additional, (1)iM_Earn, (0)iM_Advertise,
<br>
<br>(14), (13)b_OnMyAds_Slot4, (12)b_OnMyAds_Slot3, (11)b_OnMyAds_Slot2, (10)b_OnMyAds_Slot1,
<br>(9)b_adsBanner, (8)b_adsTestID, (7)b_TestApp, (6)b_AdsToday, (5)b_questToday,
<br>(4)b_GetDay, (3)b_OnPeriod, (2)b_HideT, (1)b_HideA, (0)b_HideE;
<br><hr>
[ DataBase.cs - 10033 ]
<br>5 => amo.RewardShow(),
<br>4 => amo.RewaFVShow(),
<br>3 => amo.FullViewShow(),
<br>2 => amo.RandomAdmob_R_RF(),
<br>1 => amo.RandomAdmob_RF_FV(),
<br>_ => false,
<br><hr>
[ NColor ]
<br>ushot.MaxValue => NColor.BlurDeep,
<br>110 => NColor.Blur,
<br>99 => NColor.WhiteGray,
<br>98 => NColor.GrayWhite,
<br>97 => NColor.GrayRight,
<br>96 => NColor.GrayUp,
<br>95 => NColor.,
<br>94 => NColor.Gray,
<br>93 => NColor.,
<br>92 => NColor.GrayDark,
<br>91 => NColor.BlackUp,
<br>90 => NColor.,
<br>89 => NColor.GreenLimit,
<br>88 => NColor.GreenRight,
<br>87 => NColor.,
<br>86 => NColor.GreenUp,
<br>85 => NColor.GreenSimple,
<br>84 => NColor.Green,
<br>83 => NColor.GreenMix,
<br>82 => NColor.,
<br>81 => NColor.,
<br>80 => NColor.,
<br>79 => NColor.BlueLimit,
<br>78 => NColor.BlueSky,
<br>77 => NColor.BlueJean,
<br>76 => NColor.BlueUp,
<br>75 => NColor.,
<br>74 => NColor.Blue,
<br>73 => NColor.BlueMix,
<br>72 => NColor.,
<br>71 => NColor.,
<br>70 => NColor.,
<br>69 => NColor.RedLimit,
<br>68 => NColor.RedRight,
<br>67 => NColor.,
<br>66 => NColor.RedUp,
<br>65 => NColor.,
<br>64 => NColor.Red,
<br>63 => NColor.RedMix,
<br>62 => NColor.,
<br>61 => NColor.,
<br>60 => NColor.,
<br>59 => NColor.BrownUpSkin,
<br>58 => NColor.BrownSkin,
<br>57 => NColor.BrownDeepSkin,
<br>56 => NColor.BrownUp,
<br>55 => NColor.BrownSimple,
<br>54 => NColor.Brown,
<br>53 => NColor.BrownMix,
<br>52 => NColor.BrownDeep,
<br>51 => NColor.BrownDark,
<br>50 => NColor.BrownDeepDark,
<br>49 => NColor.YellowLimit,
<br>48 => NColor.YellowRight,
<br>47 => NColor.YellowJean,
<br>46 => NColor.YellowUp,
<br>45 => NColor.YellowSimple,
<br>44 => NColor.Yellow,
<br>43 => NColor.YellowMix,
<br>42 => NColor.YellowDeep,
<br>41 => NColor.,
<br>40 => NColor.,
<br>39 => NColor.PurpleLimit,
<br>38 => NColor.,
<br>37 => NColor.,
<br>36 => NColor.,
<br>35 => NColor.,
<br>34 => NColor.,
<br>33 => NColor.,
<br>32 => NColor.,
<br>31 => NColor.,
<br>30 => NColor.,
<br>29 => NColor.AquaLimit,
<br>28 => NColor.,
<br>27 => NColor.,
<br>26 => NColor.,
<br>25 => NColor.,
<br>24 => NColor.,
<br>23 => NColor.,
<br>22 => NColor.,
<br>21 => NColor.,
<br>20 => NColor.,
<br>19 => NColor.Luz_250,
<br>18 => NColor.Luz_240,
<br>17 => NColor.Luz_220,
<br>16 => NColor.Luz_200,
<br>15 => NColor.Luz_150,
<br>14 => NColor.Luz_100,
<br>13 => NColor.,
<br>12 => NColor.Luz_50,
<br>11 => NColor.Luz_20,
<br>10 => NColor.Luz_0,
<br>9 => NColor.Placeholder,
<br>8 => NColor.,
<br>7 => NColor.,
<br>6 => NColor.,
<br>5 => NColor.,
<br>4 => NColor.,
<br>3 => NColor.,
<br>2 => Color.White,
<br>1 => Color.Black,
<br>_ => Color.Clear,
<br><hr>
