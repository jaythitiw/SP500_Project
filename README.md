# DADS5001 Mini-Project

## Topic : SP500_Project

By 1: Thitiwat Tanasuthiseri 6510422015

   2: Suthida Jumlongrasd  6510422025
## Dataset
1.S&P 500 Index 

  source : https://www.liberatedstocktrader.com/sp-500-companies/
  
2.S&P 500 Price//Golg spot // Nasdaq 
  
  source : http://www.aspen4browser.com/
  
3.Set 50 Index Price

  source : https://th.investing.com/indices/set-50-historical-data
  
4.Bond yield rate

  source : https://dqydj.com/sp-500-dividend-yield/
  
5.ตัวเลข CPI // PPI

  source : https://fred.stlouisfed.org/series/CPIAUCSL
  
6.ตัวเลข PPI

  source : https://fred.stlouisfed.org/series/PPIACO

## จุดประสงค์ของการวิเคราะห์ข้อมูลชุดนี้

1.เพื่อดูชุดข้อมูลของ S&P500 และแบ่งประเภทแต่ละ sector

2.วิเคราะห์ Market cap ของตลาด S&P500

3.วิเคราะห์ Maximum drawdow และผลตอบแทนในการลงทุนในแต่ละปี

4.เพื่อศึกษา correlation ระหว่าง S&P500 กับ ดัชนี Indexอื่นๆ Bond Yield และตัวเลขเศรษฐกิจ ต่างๆ

5.สรุปผลเพื่อนดู อัตราผลตอบแทนว่าลงทุนใน สินทรัพย์ไหน ให้ผลตอบแทนดีที่สุด

# S&P500 คืออะไร ส่วนใหญ่เป็นหุ้น Sectors รวมทั้งตลาด Sector ไหนใหญ่ที่สุด
S&P 500 คือ ดัชนีตลาดหุ้นที่ติดตามหุ้นของบริษัทขนาดใหญ่ในสหรัฐจำนวน 500 บริษัท ซึ่งแสดงถึงผลประกอบการของบริษัทจดทะเบียนในตลาดหุ้นของอเมริกากว่า 500 บริษัท 
ตัวอย่าง บริษัท ที่อยู่ใน ดัชนี S&P 500 เช่น Amazon,American Airlines Group,Bank of America, BlackRock, CME Group, Apple, Facebook, Microsoft, Google และ Tesla เป็นต้น

* S&P500 มี Sector ใดบ้าง และ Sector ไหนมากที่สุด
   ![image](https://user-images.githubusercontent.com/114090355/226168124-0faf6aa6-d986-4bf1-8163-9b6e1dbe19cb.png)
   ![image](https://user-images.githubusercontent.com/114090355/226168335-60a82bcf-fce0-4a47-9373-95fe194704f1.png)
   ![image](https://user-images.githubusercontent.com/114090355/226170306-1e49cf24-aa2f-494b-83ad-f1d5cca7aa99.png)

จากภาพจะเห็นว่าหุ้นที่อยู่บน S&P500 มีมากถึง 19 Sectors โดย 3 อันดับแรก มีจำนวนหุ้น ดังนี้

      1.Finance ซึ่งมีมากถึง 94 หุ้น

      2.Electronic Technology 52 หุ้น

      3.Health Technology 45 หุ้น



* แล้วหุ้นไหนที่มี capitalization มากที่สุดและมี Impact กับตลาดมากที่สุด

   ![image](https://user-images.githubusercontent.com/114090355/226168322-2581a67a-a4e3-4a9f-af6c-e1358e923255.png)
   ![image](https://user-images.githubusercontent.com/114090355/226184314-b6a49e64-9bdf-40b1-82a8-90e411b2906d.png)
   ![image](https://user-images.githubusercontent.com/114090355/226181242-45fb2781-55af-42ab-acc9-8af37daa3fa3.png)

   ณ ปัจจุบัน หุ้น Apple Inc. มี Market Cap. มากที่สุด ซึ่งเป็นหุ้น Sector Electronic Technology  โดยมี Market Cap.ประมาณ $2,122 Billion และมีสัดส่วน 23.54% ของ Top10 
  รองลงมาจะเป็นหุ้น Microsoft Corporation มีMarket Cap. $1,778 Billion(19.72% ของ Top10) และ หุ้น Alphabet Inc.(GOOGLE)   มีMarket Cap. $1,184 (13.14% ของ Top10)
  จะเห็นว่า ถึงแม้ว่าจำนวนหุ้นส่วนใหญ่ใน S&P500 จะเป็นหุ้น Finance แต่หุ้นที่มี Market cap. size มากที่สุดจะเป็นหุ้นประเภท Technology
  
  สรุปได้ว่า หุ้นที่ Impact กับ S&P500 มากที่สุดจะเป็นหุ้น APPLE และ Sector ที Impact กับ S&P500 จะเป็น Sector ที่เป็น Technology 


# S&P500 มีความสัมพันธ์อย่างไรกับตลาดทองคำและดัชนี Nasdaq

จากภาพจะเป็นดัชนี S&P500 5 ปี ย้อนหลัง 
![image](https://user-images.githubusercontent.com/114090355/226186214-ab4e5bae-1ed9-4873-a587-edf468902dd4.png)

เมื่อนำ S&P500มาหาความสัมพันธ์กับดัชนีสำคัญอื่นๆ เช่น ทองคำ หรือ ดัชนี NASDAQ(ดัชนีแนสแดคส่วนใหญ่จะเป็นบริษัทใหญ่ในอุตสาหกรรมเทคโนโลยี)
   
![image](https://user-images.githubusercontent.com/114090355/226186204-452d00e5-bcb1-4540-9b47-831edac21b7a.png)

จากกราฟพบว่า ดัชนี S&P500 มีเทรนที่คล้ายคลึงกับ NASDAQ เนื่องจากมูลค่า S&P500 ส่วนใหญ่เป็นหุ้น Technology แต่เมื่อเทียบกับทองคำ พบว่าไม่ได้มีเทรนที่คล้ายคลึงกัน โดยพิสูจน์ได้จากการ Correlation ระหว่าง S&P500 กับ NASDAQ และ S&P500 กับ ทองคำ ตามด้านล่าง
![image](https://user-images.githubusercontent.com/114090355/226186193-7ac90e3e-d1d7-477e-99cb-1cbbfbdd7879.png)


# แล้ว 5 ปีที่ผ่านมาดัชนีไหนโตไวกว่ากัน
![image](https://user-images.githubusercontent.com/114090355/226186163-b8c1efef-da8f-4261-86a1-3107a0e5bc59.png)

   จากตารางด้านบน พบว่า 5 ปีผ่านมา ดัชนี NASDAQ เติบโตมากที่สุด ถึง 65.9% รองลงมาจะเป็น ทองคำ อยู่ที่ 48% และS&P500 43% ซึ่งสามารถบ่งบอกได้ว่า 5 ปีที่ผ่านเศรษกิจของสหรัฐอเมริกาเติบโตอย่ารวดเร็วเนื่องจากการเติบโตของหุ้น Tech ที่เติบโตแบบก้าวกระโดด

และถ้าหากลงทุนกองทุน 3 ดัชนี แล้วซื้อต้นปีแล้วขายปลายปี จะได้ผลตอบแทนตามภาพด้านล่าง
![image](https://user-images.githubusercontent.com/114090355/226186138-4f16f9dd-95ec-49a7-8165-08e9774c866a.png)

พบว่า ดัชนี S&P500 กับ NASDAQ มีความผันผวนที่สูงเมื่อเทียบกับทองคำ ซึ่งในปี 2019 และ 2020 มีผลตอบแทนที่สูง ประมาณ30-40% แต่ทองคำสูงสุดที่ 25%
โดย S&P500 มีความผันผวนน้อยกว่า NASDAQ เนื่องจาก S&P500 มี Sector อื่นที่กระจายความเสี่ยงมากกว่า NASDAQ ซึงมีแต่หุ้น TECH
ทำให้ปี 2022 ที่เกิดปัญหาสงครามรัสเซีย-ยูเครน และ การขึ้นดอกเบี้ยของ FED ทำให้ NASDAQ ลดลงไปถึง 33.5% ในขณะที่ S&P500 ลดลง 19.6% แต่เมื่อเทียบกับทองคำแล้ว ทองคำลดลงเพียง 0.2%


# ตัวเลขทางเศรษฐกิจใดส่งผลกระทบกับ S&P500 มากที่สุด

* PPI & CPI\
   PPI ตัวเลขทางสถิติวัดแรงกดดันเงินเฟ้อที่มาจากฝั่งผู้ผลิต ทั้งนี้ PPI ที่ไม่รวมพวกอาหารและพลังงานจะเรียกว่า Core PPI ซึ่งจะถูกจับตามองมากกว่าเพราะจะมีผลกับอัตราเงินเฟ้อ\
   CPI ตัวเลขทางสถิติที่ใช้วัดการเปลี่ยนแปลงของราคาสินค้าและบริการที่ครอบครัวหรือผู้บริโภคซื้อหามาบริโภคเป็นประจำ 
   
   ![image](https://user-images.githubusercontent.com/114090355/226186241-d5b8249e-4c49-4c0e-af00-b045c1f9ed31.png)\
   
   จากภาพพบว่า PPI มีเทรนที่คล้ายคลึงกับดัชนี S&P500 มากกว่า CPI เนื่องจาก PPI ไม่รวมอาหารและพลังงาน แต่ CPI กลับเพิ่มขึ้นเรื่อยๆ สรุปได้ว่าเงินเฟ้อเพิ่มขึ้นเรื่อยๆโดยไม่มีผลกับดัชนี S&P 500
   
* GDP
   GDP คือ ดัชนี้การที่นับรายได้ที่เกิดขึ้นจากในประเทศเท่านั้น
   ![image](https://user-images.githubusercontent.com/114090355/226186278-79016f06-e555-4d08-95f8-d8e9e974e23a.png)\
      จากกราฟพบว่า GDP ของ สหรัฐอเมริกาเพิ่มขึ้นเรื่อยๆ แต่ในปี 2022 หุ้นS&P500 ตกลง ดังนั้นจึงสรุปได้ว่า GDP ไม่ค่อยมีผลต่อราคาดัชนี S&P500
		


  * BondYield & FED Fund Rate\
  	BondYield คือ  เป็นผลตอบแทนที่นักลงทุนคาดหวังจากการถือครองพันธบัตรรัฐบาล ซึ่งผู้ลงทุนจะได้ผลตอบแทนในรูปของ "ดอกเบี้ย" \
	Fed fund Rate คือ  อัตราดอกเบี้ยเป้าหมายที่มีอิทธิพลต่อจำนวนเงินที่ธนาคารในสหรัฐอเมริกาเรียกเก็บจากการปล่อยกู้ข้ามคืน\
	
	![image](https://user-images.githubusercontent.com/114090355/226187358-33c36ed3-47cd-4a89-9693-f47c8774fd39.png)\
      จากกราฟ BondYield10Y เมื่อเทียบกับ S&P500 จะพบว่าเมื่อ Bond Yield สูงขึ้น แต่ S&P500 กลับปรับตัวลง เนื่องจากค่าผลตอบแทนที่ได้จากการถือครองพันธบัตรสูงขึ้น ทำให้นักลงทุนปรับลดการลงทุนจากหุ้น และนำทรัพย์สินมาลงทุนที่พันธบัตรมากขึ้น/
      และยังพบได้อีกว่า Fed fund Rate ก็เป็นอีกปัจจัยที่ทำให้นักลงทุนถอนเงินจากหุ้นมาฝากเงินธนาคารเนื่องจากดอกเบี้ยที่สูงขึ้นมากกว่าผลตอบแทนจากการถือหุ้น
      
  สรุปได้ว่าปัจจัยหลักที่มีผลต่อดัชนี S&P500 คือ BondYield และ การขึ้นดอกเบี้ยของ FED 
  
  
  # ถ้าเป็นนักลงทุนจะลงทุนในดัชนี S&P500 ดีไหม
  
   การลงทุนในกองทุนหรือหุ้นนั้นย่อมมีความเสี่ยง ขึ้นอยู่กับพฤติกรรมและการยอมรับความเสี่ยงของแต่ละบุคคล
   
   * จาก Maximun drawdown ของ 5 ปีย้อนหลังจะพบว่าถ้าหากซึ่งจุดต่ำสุดและขายที่จุดสูงสุดของแต่ละปี จะได้ผลดังกราฟ
   ![image](https://user-images.githubusercontent.com/125905968/226210846-6e49741a-abb8-4443-bd51-609b6abba910.png)


     พบว่าในปี 2020 ถ้าหากเราซื้อที่จุดต่ำสุดและนำไปขายที่จุดสูงสุด จะทำให้เราได้กำไรมากถึง 40 % เนื่องจากปีดังกล่าวมีความผันผวนสูงเนื่องจากสถานการณ์โควิด 2019 สำหรับปีอื่นอยู่ที่ประมาณ 20-25 %
      
   * ถ้าหากว่าเราเป็นนักลงทุน S&P500 ค่าเฉลี่ยผลตอบแทน ในแต่ละปี ได้ผลดังกราฟด้านล่าง

![image](https://user-images.githubusercontent.com/125905968/226210535-04297c42-f85e-41a6-bc77-26d6f3168f18.png)

   
