# การบ้าน

1. โดยทั่วไป การพัฒนาซอฟต์แวร์แบบ incremental developement นั้น จะเหมาะกับการสร้างซอฟต์แวร์ที่ user เองก็ยังมีไอเดียไม่ชัดเจน หรือยังไม่รู้ความต้องการของตัวเอง  ในคำกล่าวข้างต้น เป็นจริงหรือไม่ จงอภิปราย
ตอบ ใช่ เพราะ ไม่ได้ เพราะ ต้องแบ่งระบบงานออกเป็นระบบ ย่อยต่างๆ และ มีการนำระบบย่อยๆมารวมกัน จะมีความเสี่ยงสูง เนื่องจากยังมีไอเดียไม่ชัดเจน
2. จงเปรียบเทียบข้อแตกต่าง (ข้อดี-ข้อเสียหรือข้อจำกัด) ระหว่างกระบวนการพัฒนาซอฟต์แวร์แบบต่างๆ ที่ท่านรู้จัก 
ตอบ  ข้อดี Waterfall Model
      1.แบ่งงานยากให้เป็นงานที่เล็ก ง่ายต่อการจัดการ
      2.มีการกำหนดProductที่ต้องส่งมอบในแต่ละงาน อย่างชัดเจน
      ข้อจำกัด Waterfall Model
      1.ค้นพบข้อผิดพลาดของขั้นที่เสร็จสิ้นแล้ว ไม่สามารถแก้ไขได้ การแก้ไขจำเป็นต้องเริ่มรอบ
      2.ลูกค้าเห็นและทดลองใช้Software ก็ต่อเมื่อถึงขั้นตอนสุดท้า 
     ข้อดี incremental developement
     1.ทำงานได้สำเร็จมากขึ้นและตัวโปรแกรมมีปัญหาน้อยลง
     2.จัดการความเสี่ยงได้ตั้งแต่เนิ่นๆ
     3.ลดความซับซ้อนของตัวระบบ เพราะได้ทำการแบ่งงานเป็นระบบย่อยๆ ทำให้ทำงานง่ายขึ้น
     4.ได้รับ feedback และการทดลองใช้ได้เร็ว ทำให้ได้ระบบที่ตรงกับความต้องการของผู้ใช้มากขึ้น
     ข้อจำกัด incremental developement
     1.ถ้า phase แรกทำงานล่าช้าจะทำให้ขึ้น phase 2ไม่ได้
     2.หลุดจากเป้าหมายได้ง่ายพราะทุกคนในทีมจะเน้นไปที่การจบ phase แต่จะยังใช้งานไม่ได้ จะต้องทำให้จบทั้งโปรเจ็คก่อน

3. จงบอกข้อแตกต่างระหว่าง user requirement และ system requirement
ตอบ user requirement เป็นความต้องการที่รวบรวมจากผู้ใช้ระบบโดยตรง จะเจอปัญหา ยากต่อการทำความเข้าใจ  มีความสับสน ความต้องการผสมรวมกัน
    system requirement เป็นการกำหนดความต้องการของระบบ ฟังก์ชันและบริการต่างๆ

4. จงยกตัวอย่างเทคโนโลยีที่มีซอฟต์แวร์เข้ามามีส่วนร่วมในอดีต ที่ทำให้คนต้องออกจากงานจำนวนมาก และให้เหตุผลที่เป็นเช่นนั้น
5. จากข้อ 3. ในฐานะนักวิศวกรรมซอฟค์แวร์ ท่านมีโอกาสที่จะถูกให้ออกจากงานหรือไม่  และ    ถ้าไม่อยากถูกให้ออกจากงาน ท่านคิดว่าควรทำงานในส่วนใดของกระบวนการ  
ตอบ Automation Machine เพราะ งานจะถูกแทนที่ด้วยระบบอัตโนมัติ และ ลดการทำงานของมนุษย์ลง

5. จากข้อ 3. ในฐานะนักวิศวกรรมซอฟค์แวร์ ท่านมีโอกาสที่จะถูกให้ออกจากงานหรือไม่  และ    ถ้าไม่อยากถูกให้ออกจากงาน ท่านคิดว่าควรทำงานในส่วนใดของกระบวนการ 
ตอบ ไม่มีโอกาศ เพราะ ไม่ได้กระทำผิด