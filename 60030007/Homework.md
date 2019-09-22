1. โดยทั่วไป การพัฒนาซอฟต์แวร์แบบ incremental developement นั้น จะเหมาะกับการสร้างซอฟต์แวร์ที่ user เองก็ยังมีไอเดียไม่ชัดเจน หรือยังไม่รู้ความต้องการของตัวเอง ในคำกล่าวข้างต้น เป็นจริงหรือไม่ จงอภิปราย
ตอบ incremental developement คือ การนำงานมาแบ่งเป็นงานย่อย โดยจะทำการพัฒนาระบบงานที่เป็นงานหลักของระบบก่อน จากนั้นพัฒนาต่อเติมในแต่ละ Incrementตามลำดับ จนกระทั้งแล้วเสร็จ
2. จงเปรียบเทียบข้อแตกต่าง (ข้อดี-ข้อเสียหรือข้อจำกัด) ระหว่างกระบวนการพัฒนาซอฟต์แวร์แบบต่างๆ ที่ท่านรู้จัก
ตอบ water fall model ข้อดีคือ ทำให้ง่ายในการควบคุมความคืบหน้าในการพัฒนา พัฒนาระบบได้ตรงตามเวลาที่กำหนด ข้อเสียคือ ต้องดำเนินตามขั้นตอนให้เสร็จสิ้นก่อนจึงจะดำเนินการขั้นตอนต่อไป ซึ่งหากเป็นโครงการโหญ่อาจต้องใช้เวลามากทำให้เสียเวลาย้อนกลับ และมีความเสี่ยงสูง
increment model ข้อดีคือ สามารถทำโครงการซอฟต์แวร์ขนาดใหญ่ไ้ โดยแบ่งงานเป็นระบบย่อย โดยพัฒนาระบบงานหลักก่อน แล้วค่อยต่อเติมในแต่ละอัน ข้อเสียคือมีความเสี่ยงสูง เนื่องจากมีการนำระบบย่อยมาประกอบรวมกัน และอาจทำให้งานสะดุด
3. จงบอกข้อแตกต่างระหว่าง user requirement และ system requirement
ตอบ User Requirement - เป็นความต้องการที่รวบรวมจากผู้ใช้ระบบโดยตรง เช่น ลำดับของช่องที่จะให้กรอกข้อมูล, จะกรอกอย่างไร, เรียงลำดับอย่างไร, ขนาดตัวอักษร, สีอะไร เป็นต้น
System Requirement – ความต้องการของระบบ เช่น ระบบต้องสามารถส่งข้อมูลผ่านระบบเครือข่ายได้, ข้อมูลต้องเก็บได้ทั้งที่ Server และ Work Station เป็นต้น
4. จงยกตัวอย่างเทคโนโลยีที่มีซอฟต์แวร์เข้ามามีส่วนร่วมในอดีต ที่ทำให้คนต้องออกจากงานจำนวนมาก และให้เหตุผลที่เป็นเช่นนั้น
ตอบ เทคโนโลยีในการธนาคาร ที่ในปัจจุบันใช้เป็นแอพพลิเคชั่นในการชำระเงิน โอนผ่านโทรศัพท์มือถือ จึงทำให้ไม่จำเป็นต้องไปที่ธนาคารเองก็ได้ จึงทำให้ลดปริมาณพนักงานลงจำนวนมาก 
5. จากข้อ 4. ในฐานะนักวิศวกรรมซอฟค์แวร์ ท่านมีโอกาสที่จะถูกให้ออกจากงานหรือไม่ และ ถ้าไม่อยากถูกให้ออกจากงาน ท่านคิดว่าควรทำงานในส่วนใดของกระบวนการ
ตอบ ในฐานะนักพัฒนาซอฟต์แวร์ ไม่น่าจะมีโอกาสได้ออกจากงาน เพราะเนื่องจากนักพัฒนาซอฟต์แวร์ยังจำเป็นที่จะต้องดูแลซอฟต์แวร์ที่เข้ามาทำงานทำหน้าที่แทนคน แต่ถ้าไม่อยากออกจากงาน ควรทำในส่วนของพัฒนาซอฟต์แวร์
เพราะว่า ซอฟต์แวร์จำเป็นที่จะต้องมีคนคอยควบคุมดูแลและพัฒนาต่อไป