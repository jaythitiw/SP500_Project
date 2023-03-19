# DADS5001 Mini-Project

## Topic : SP500_Project

By 1: Thitiwat Tanasuthiseri 6510422015
   2: Suthida Jumlongrasd  6510422025
## Dataset
1.S&P 500 Index 

  source : https://www.liberatedstocktrader.com/sp-500-companies/
  
2.S&P 500 Price//Golg spot // Nasdaq 
  
  source : 
  
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

4.เพื่อศึกษา correration ระหว่าง S&P500 กับ ดัชนี Indexอื่นๆ Bond Yield และตัวเลขเศรษฐกิจ ต่างๆ

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
   ![image](https://user-images.githubusercontent.com/114090355/226168029-e9e0bef9-2cc0-45b6-bcaa-92d9361aafb2.png)

   ณ ปัจจุบัน หุ้น Apple Inc. มี Market Cap. มากที่สุด ซึ่งเป็นหุ้น Sector Electronic Technology  โดยมี Market Cap.ประมาณ $2,122 Billion และมีสัดส่วน 23.54% ของ Top10 
  รองลงมาจะเป็นหุ้น Microsoft Corporation มีMarket Cap. $1,778 Billion(19.72% ของ Top10) และ หุ้น Alphabet Inc.(GOOGLE)   มีMarket Cap. $1,184 (13.14% ของ Top10)
  จะเห็นว่า ถึงแม้ว่าจำนวนหุ้นส่วนใหญ่ใน S&P500 จะเป็นหุ้น Finance แต่หุ้นที่มี Market cap. size มากที่สุดจะเป็นหุ้นประเภท Technology
  
  สรุปได้ว่า หุ้นที่ Impact กับ S&P500 มากที่สุดจะเป็นหุ้น APPLE และ Sector ที Impact กับ S&P500 จะเป็น Sector ที่เป็น Technology 


# S&P500 มีความสัมพันธ์อย่างไรกับตลาดทองคำและดัชนี Nasdaq

จากภาพจะเป็นดัชนี S&P500 5 ปี ย้อนหลัง 
![image](https://user-images.githubusercontent.com/114090355/226166307-877f8d9c-e77e-4346-8fb9-97f1f70bb76e.png)

เมื่อนำ S&P500มาหาความสัมพันธ์กับดัชนีสำคัญอื่นๆ เช่น ทองคำ หรือ ดัชนี NASDAQ(ดัชนีแนสแดคส่วนใหญ่จะเป็นบริษัทใหญ่ในอุตสาหกรรมเทคโนโลยี)
   
![image](https://user-images.githubusercontent.com/114090355/226171409-d4cf2463-b1ff-416f-b13f-23879d103b68.png)

จากกราฟพบว่า ดัชนี S&P500 มีเทรนที่คล้ายคลึงกับ NASDAQ เนื่องจากมูลค่า S&P500 ส่วนใหญ่เป็นหุ้น Technology แต่เมื่อเทียบกับทองคำ พบว่าไม่ได้มีเทรนที่คล้ายคลึงกัน โดยพิสูจน์ได้จากการ Correlation ระหว่าง S&P500 กับ NASDAQ และ S&P500 กับ ทองคำ ตามด้านล่าง
![image](https://user-images.githubusercontent.com/114090355/226172619-ae1a6514-bc61-42d6-b6a8-4e75db2b5d87.png)


# แล้ว 5 ปีที่ผ่านมาดัชนีไหนโตไวกว่ากัน
![image](https://user-images.githubusercontent.com/114090355/226177100-8454ce9f-fe0e-4191-b81b-17c1a810dcde.png)

   จากตารางด้านบน พบว่า 5 ปีผ่านมา ดัชนี NASDAQ เติบโตมากที่สุด ถึง 65.9%  รองลงมาจะเป็น S&P500 อยู่ที่ 52% และทองคำ 48% ซึ่งสามารถบ่งบอกได้ว่า 5 ปีที่ผ่านเศรษกิจของสหรัฐอเมริกาเติบโตอย่ารวดเร็วเนื่องจากการเติบโตของหุ้น Tech ที่เติบโตแบบก้าวกระโดด

และถ้าหากลงทุนกองทุน 3 ดัชนี แล้วซื้อต้นปีแล้วขายปลายปี จะได้ผลตอบแทนตามภาพด้านล่าง
![image](https://user-images.githubusercontent.com/114090355/226177392-26b9406e-bb01-41d9-966b-e34730d11de2.png)


