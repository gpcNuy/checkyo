# 1.0.23
<br>sign(0)SFS_VerNic == "DecideOld", "DecideOld", "Old"
<br>sign(1)SFS_Letter
<br>
<br>xyz(0)SFF_Estimate == old_Op.estimate
<br>xyz(1)SFF_TransEstimate
<br>xyz(2)SFF_empty
<br>xyz(3)SFF_CDA1_Value
<br>xyz(4)SFF_CDA2_Value
<br>xyz(5)SFF_CDA3_Value
<br>xyz(6)SFF_CDA4_Value
<br>
<br>set(0)SFIS_Language
<br>set(1)SFIS_FrontVersion
<br>set(2)SFIS_BackVersion
<br>set(3)SFIS_CDA1_Day
<br>set(4)SFIS_CDA2_Day
<br>set(5)SFIS_CDA3_Day
<br>set(6)SFIS_CDA4_Day
<br>set(7)SFIS_BoxFont
<br>set(8)SFIS_MemoFont
<br>set(9)SFIS_OtherFont
<br>
<br>memory(0)SFIM_Advertise == old_Op.advertisePonit
<br>memory(1)SFIM_Earn == old_Op.expense
<br>memory(2)SFIM_Additional
<br>memory(3)SFIM_Total == old_Op.total
<br>memory(4)SFIM_Period == old_Op.period
<br>memory(5)SFIM_Attend == old_Op.payDay
<br>memory(6)SFIM_SelectYY == old_Op.selectYY
<br>memory(7)SFIM_SelectMM == old_Op.selectMM
<br>memory(8)SFIM_SelectDD
<br>
<br>onOff(0)SFB_HideE == old_Op.seeEndHideE
<br>onOff(1)SFB_HideT == old_Op.seeEndHideT
<br>onOff(2)SFB_OnPeriod == old_Op.calcuratingPeriod
<br>onOff(3)SFB_HaveOld
<br>onOff(4)SFB_GetDay
<br>
<br>(OptionJson)total, payDay, selectYY, selectMM
<br>for (int i = 0; i < old_Sch.Count; i++)
<br>  Combine temp = new Combine(old_Sch[i].year, old_Sch[i].month, old_Sch[i].day);
<br>  temp.sign[CsLt.CBS_ID] = old_Sch[i].identification;
<br>  temp.sign[CsLt.CBS_Memo] = old_Sch[i].account;
<br>  temp.xyz[CsLt.CBF_Estimate] = old_Sch[i].focus;
<br>  SignNorm.sf.combine.Add(temp);
<br><hr>
