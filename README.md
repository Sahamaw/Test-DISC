<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DISC Test</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }
    .container {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    h1 {
      text-align: center;
      color: #4CAF50;
    }
    .question {
      margin-bottom: 20px;
    }
    .question h3 {
      margin-bottom: 10px;
    }
    .options {
      list-style: none;
      padding: 0;
    }
    .options li {
      margin-bottom: 10px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background-color: #45a049;
    }
    .result {
      text-align: center;
      margin-top: 20px;
      font-size: 18px;
      font-weight: bold;
    }
    .result img {
      max-width: 150px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>DISC Test</h1>
    <form id="discTestForm">
      
<!-- Question 1 -->
<div class="question" data-question="1">
  <h3>เมื่อคุณต้องแก้ปัญหาในสถานการณ์ยากลำบาก คุณมักจะ :</h3>
  <h3>ခက်ခဲတဲ့အခြေအနေတွေကို ရင်ဆိုင်ရတဲ့အခါ :</h3>
  <ul class="options">
    <li><label><input type="radio" name="q1" value="D"> ตัดสินใจอย่างรวดเร็วและลงมือทำทันที / ဆုံးဖြတ်ချက်တွေကို မြန်မြန်ချပြီး ချက်ချင်းအရေးယူပါ။ </label></li>
    <li><label><input type="radio" name="q1" value="I"> พยายามหาวิธีที่ทุกคนจะพอใจ / လူတိုင်း စိတ်ကျေနပ်စေမယ့် နည်းလမ်းကို ရှာကြည့်ပါ။ </label></li>
    <li><label><input type="radio" name="q1" value="S"> รักษาความสงบและค่อยๆ คิดหาทางออก / စိတ်အေးအေးထားပြီး ဖြည်းဖြည်းချင်း ထွက်သွားဖို့ စဉ်းစားပါ။ </label></li>
    <li><label><input type="radio" name="q1" value="C"> วิเคราะห์ข้อมูลทั้งหมดก่อนตัดสินใจ / ဆုံးဖြတ်ချက်မချမီ အချက်အလက်အားလုံးကို ခွဲခြမ်းစိတ်ဖြာပါ။ </label></li>
  </ul>
</div>

<!-- Question 2 -->
<div class="question" data-question="2">
  <h3>เมื่อทำงานในทีม คุณมักจะ:</h3>
  <h3>အဖွဲ့လိုက် အလုပ်လုပ်တဲ့အခါ:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q2" value="D"> ชอบเป็นผู้นำและควบคุมทิศทาง / ဦးဆောင်လမ်းပြခြင်းကို နှစ်သက်သည်။ </label></li>
    <li><label><input type="radio" name="q2" value="I"> สร้างบรรยากาศที่เป็นมิตรและสนุกสนาน / ဖော်ရွေပြီး ပျော်စရာကောင်းတဲ့ လေထုကို ဖန်တီးပါ။ </label></li>
    <li><label><input type="radio" name="q2" value="S"> สนับสนุนและช่วยเหลือเพื่อนร่วมทีม / အသင်းဖော်တွေကို ပံ့ပိုးကူညီပါ။ </label></li>
    <li><label><input type="radio" name="q2" value="C"> เน้นความถูกต้องและรายละเอียดของงาน / အလုပ်၏ တိကျမှုနှင့် အသေးစိတ်ကို အလေးထားပါ။ </label></li>
  </ul>
</div>

<!-- Question 3 -->
<div class="question" data-question="3">
  <h3>คุณรู้สึกพอใจเมื่อ:</h3>
  <h3>ဘယ်အချိန်မှာ စိတ်ကျေနပ်မှုခံစားရလဲ။:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q3" value="D"> คุณสามารถบรรลุเป้าหมายที่ท้าทาย / စိန်ခေါ်တဲ့ ပန်းတိုင်ကို သင်အောင်မြင်နိုင်ပါတယ်။ </label></li>
    <li><label><input type="radio" name="q3" value="I"> คุณได้รับการยอมรับและชื่นชมจากผู้อื่น / သင်သည် အခြားသူများထံမှ အသိအမှတ်ပြုမှုနှင့် ချီးမွမ်းခြင်းကို ရရှိသည်။ </label></li>
    <li><label><input type="radio" name="q3" value="S"> ทุกอย่างดำเนินไปอย่างราบรื่นและมั่นคง / အရာအားလုံး ချောချောမွေ့မွေ့ ဖြစ်သွားတယ်။ </label></li>
    <li><label><input type="radio" name="q3" value="C"> งานของคุณไร้ที่ติและสมบูรณ์แบบ / မင်းလုပ်တဲ့အလုပ်က ပြီးပြည့်စုံတယ်။ </label></li>
  </ul>
</div>

<!-- Question 4 -->
<div class="question" data-question="4">
  <h3>เมื่อคุณต้องตัดสินใจในสถานการณ์ที่ไม่แน่นอน คุณมักจะ:</h3>
  <h3>မသေချာမရေရာတဲ့ အခြေအနေတွေမှာ ဆုံးဖြတ်ချက်တွေ ချရတဲ့အခါ:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q4" value="D"> ตัดสินใจทันทีโดยไม่ลังเล / မဆိုင်းမတွ ချက်ချင်းဆုံးဖြတ်ပါ။ </label></li>
    <li><label><input type="radio" name="q4" value="I"> ขอความเห็นจากเพื่อน / သင့်သူငယ်ချင်းများ၏ ထင်မြင်ယူဆချက်များကို မေးမြန်းပါ။ </label></li>
    <li><label><input type="radio" name="q4" value="S"> รอจนกว่าจะมีข้อมูลเพิ่มเติม / မဆုံးဖြတ်မီ အချက်အလက်များ ပိုမိုရရှိလာသည်အထိ စောင့်ပါ။ </label></li>
    <li><label><input type="radio" name="q4" value="C"> วิเคราะห์ทุกแง่มุมอย่างละเอียด / ရှုထောင့်တိုင်းကို အသေးစိတ်ခွဲခြမ်းစိတ်ဖြာပါ။ </label></li>
  </ul>
</div>

<!-- Question 5 -->
<div class="question" data-question="5">
  <h3>เมื่อคุณอยู่ในสถานการณ์ที่มีความขัดแย้ง คุณมักจะ:</h3>
  <h3>သင်သည် ပဋိပက္ခအခြေအနေတွင် ရှိနေရမည်။:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q5" value="D"> เผชิญหน้าและแก้ไขปัญหาโดยตรง / ပြဿနာတွေကို ထိပ်တိုက်ရင်ဆိုင်ဖြေရှင်းပါ။ </label></li>
    <li><label><input type="radio" name="q5" value="I"> พยายามทำให้ทุกคนพอใจ / လူတိုင်း စိတ်ကျေနပ်စေမယ့် နည်းလမ်းကို ရှာကြည့်ပါ။ </label></li>
    <li><label><input type="radio" name="q5" value="S"> หลีกเลี่ยงความขัดแย้งและหาทางประนีประนอม / ပဋိပက္ခကို ရှောင်ကြဉ်ပြီး အပေးအယူကို အသုံးပြုပါ။ </label></li>
    <li><label><input type="radio" name="q5" value="C"> ใช้ข้อเท็จจริงและเหตุผลในการแก้ไข / ပြဿနာများကိုဖြေရှင်းရန် အချက်အလက်များနှင့် အကြောင်းပြချက်ကို အသုံးပြုပါ။ </label></li>
  </ul>
</div>

<!-- Question 6 -->
<div class="question" data-question="6">
  <h3>คุณชื่นชอบการทำงานแบบไหนมากที่สุด:</h3>
  <h3>ဘယ်လိုအလုပ်ပုံစံကို အကြိုက်ဆုံးလဲ။:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q6" value="D"> การทำงานที่มีเป้าหมายชัดเจนและท้าทาย / ရှင်းလင်းပြတ်သားပြီး စိန်ခေါ်မှု ပန်းတိုင်များဖြင့် လုပ်ဆောင်ပါ။</label></li>
    <li><label><input type="radio" name="q6" value="I"> การทำงานร่วมกับผู้อื่นในบรรยากาศที่สนุกสนาน / ပျော်ရွှင်ဖွယ်ကောင်းသော အငွေ့အသက်ဖြင့် အခြားသူများနှင့် အလုပ်လုပ်ပါ။</label></li>
    <li><label><input type="radio" name="q6" value="S"> การทำงานที่มั่นคงและมีขั้นตอนชัดเจน / တည်ငြိမ်ပြီး စနစ်တကျလုပ်တယ်။ </label></li>
    <li><label><input type="radio" name="q6" value="C"> การทำงานที่ต้องใช้ความละเอียดและความแม่นยำ / တိကျမှုနှင့် တိကျမှု လိုအပ်သော အလုပ် </label></li>
  </ul>
</div>

<!-- Question 7 -->
<div class="question" data-question="7">
  <h3>คุณคิดว่าคุณเป็นคนแบบไหน:</h3>
  <h3>မင်းဘယ်လိုလူလို့ထင်လဲ။:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q7" value="D"> มุ่งมั่นและกล้าหาญ / သန္နိဋ္ဌာန်နဲ့ ရဲရင့်တယ်။ </label></li>
    <li><label><input type="radio" name="q7" value="I"> เป็นมิตรและชอบเข้าสังคม / ဖော်ရွေပြီး ပေါင်းသင်းဆက်ဆံရေး </label></li>
    <li><label><input type="radio" name="q7" value="S"> ใจเย็นและอดทน / စိတ်ရှည်ပြီး စိတ်အေးအေးထားပါ။ </label></li>
    <li><label><input type="radio" name="q7" value="C"> ละเอียดและรอบคอบ / စေ့စပ်သေချာသည်။ </label></li>
  </ul>
</div>

<!-- Question 8 -->
<div class="question" data-question="8">
  <h3>เมื่อคุณได้รับมอบหมายงานใหม่ คุณมักจะ:</h3>
  <h3>တာဝန်သစ်တစ်ခု ပေးအပ်သောအခါ:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q8" value="D"> เริ่มต้นทันทีโดยไม่ต้องรอ / ယခု စတင်လိုက်ပါ။ </label></li>
    <li><label><input type="radio" name="q8" value="I"> ชวนเพื่อนมาร่วมทำงานด้วย / သင်နှင့်အတူအလုပ်လုပ်ရန်သူငယ်ချင်းများကိုဖိတ်ခေါ်ပါ။ </label></li>
    <li><label><input type="radio" name="q8" value="S"> วางแผนอย่างละเอียดก่อนเริ่ม / မစတင်မီ သေချာစီစဉ်ပါ။ </label></li>
    <li><label><input type="radio" name="q8" value="C"> ศึกษาข้อมูลทั้งหมดก่อนลงมือ / သင်မစတင်မီ အချက်အလက်အားလုံးကို လေ့လာပါ။ </label></li>
  </ul>
</div>

<!-- Question 9 -->
<div class="question" data-question="9">
  <h3>คุณรู้สึกไม่สบายใจเมื่อ:</h3>
  <h3>ဘယ်အရာက မင်းကို စိတ်မသက်မသာဆုံးဖြစ်စေမလဲ။:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q9" value="D"> คุณไม่มีอำนาจในการตัดสินใจ / သင့်တွင် ဆုံးဖြတ်ချက်ချပိုင်ခွင့် မရှိပါ။ </label></li>
    <li><label><input type="radio" name="q9" value="I"> คุณถูกปฏิเสธจากผู้อื่น / မင်းကို တခြားသူတွေက ငြင်းပယ်တယ်။ </label></li>
    <li><label><input type="radio" name="q9" value="S"> มีการเปลี่ยนแปลงที่ไม่คาดคิด / မမျှော်လင့်ထားတဲ့ အပြောင်းအလဲတွေ ရှိတယ်။ </label></li>
    <li><label><input type="radio" name="q9" value="C"> งานที่คุณทำไม่สมบูรณ์แบบ / သင် ပြီးမြောက်ခဲ့သော အလုပ်သည် သင်မျှော်လင့်ထားသလောက် မကောင်းခဲ့ပါ။ </label></li>
  </ul>
</div>

<!-- Question 10 -->
<div class="question" data-question="10">
  <h3>เมื่อคุณต้องการแรงบันดาลใจ คุณมักจะ:</h3>
  <h3>လှုံ့ဆော်မှုလိုတဲ့အခါ:</h3>
  <ul class="options">
    <li><label><input type="radio" name="q10" value="D"> มองหาความท้าทายใหม่ / စိန်ခေါ်မှုအသစ်တွေကို သင်ရှာဖွေနေပါလိမ့်မယ်။ </label></li>
    <li><label><input type="radio" name="q10" value="I"> ขอคำปรึกษาจากเพื่อน / သူငယ်ချင်းကို အကြံဥာဏ်တောင်းပါ။ </label></li>
    <li><label><input type="radio" name="q10" value="S"> เข้าหาธรรมชาติหรือสิ่งที่สงบ / သဘာဝတရား သို့မဟုတ် ငြိမ်းချမ်းသော အရာတစ်ခုခုသို့ ဝင်ပါ။ </label></li>
    <li><label><input type="radio" name="q10" value="C"> ศึกษาข้อมูลเพิ่มเติม / ပိုမိုသိရှိရန် </label></li>
  </ul>
</div>


      <button type="button" onclick="calculateResult()">ส่งคำตอบ</button>
    </form>

    <div class="result" id="result"></div>
  </div>

  <script>
    function calculateResult() {
      const form = document.getElementById('discTestForm');
      const formData = new FormData(form);
      const scores = { D: 0, I: 0, S: 0, C: 0 };

      // Count scores
      for (let [key, value] of formData.entries()) {
        scores[value]++;
      }

      // Determine the highest score
      const highestScore = Math.max(...Object.values(scores));
      const resultType = Object.keys(scores).find(key => scores[key] === highestScore);

      // Map results to text and image
      const resultMapping = {
        D: { text: "กระทิง (Dominance)", img: "https://img5.pic.in.th/file/secure-sv1/tj6MPGeVitMTB4kTY0Y1haI4aZSckMIZLoiMYaQu.jpeg" },
        I: { text: "นกอินทรี (Influence)", img: "https://img2.pic.in.th/pic/xl8QDHRPEDAYhGYPRh1tK43mCZXwqrc0YFnz5GcZ.jpeg" },
        S: { text: "หนู (Steadiness)", img: "https://img2.pic.in.th/pic/hUCyJ7rqTHU3U54r7LqQhWUrNmD7RQexE4kBEm6q.jpeg" },
        C: { text: "หมี (Conscientiousness)", img: "https://img5.pic.in.th/file/secure-sv1/T3GFQnrI5xbV01lIFAjj9hMndcCcf3H7crqonMkR.jpeg" }
      };

      const result = resultMapping[resultType];

      // Display the result
      const resultDiv = document.getElementById('result');
      resultDiv.innerHTML = `
        <p>ผลลัพธ์ของคุณคือ: ${result.text}</p>
        <img src="${result.img}" alt="${result.text}">
      `;
    }
  </script>
</body>
</html>
