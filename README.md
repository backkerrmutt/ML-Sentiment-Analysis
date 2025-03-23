# ML-Sentiment-Analysis
Sentiment Analysis for Restaurant Reviews (การวิเคราะห์อารมณ์ความรู้สึกจากรีวิวร้านอาหาร)  
การวิเคราะห์อารมณ์ความรู้สึกในภาษาไทย

โปรเจกต์นี้เป็นส่วนหนึ่งของวิชาการเรียนรู้ของเครื่อง (Machine Learning) ที่มีเป้าหมายเพื่อศึกษาและพัฒนาโมเดลสำหรับวิเคราะห์อารมณ์ความรู้สึกของข้อความภาษาไทย โดยจำแนกความคิดเห็นออกเป็น บวก (Positive), ลบ (Negative), และเป็นกลาง (Neutral)

ภาพรวมของโปรเจกต์

โปรเจกต์นี้ใช้เทคนิค การเรียนรู้แบบมีผู้สอน (Supervised Learning) ประเภท การจำแนกข้อความ (Text Classification) ซึ่งอยู่ภายใต้สาขาของ การประมวลผลภาษาธรรมชาติ (Natural Language Processing - NLP) ข้อมูลที่ใช้ในการฝึกโมเดลคือชุดข้อมูล wisesight_sentiment ซึ่งมีป้ายกำกับที่เหมาะสมสำหรับการวิเคราะห์อารมณ์ความรู้สึก

คุณสมบัติเด่นของโปรเจกต์

การประมวลผลข้อความภาษาไทยเบื้องต้น (Tokenization, การตัดคำ, การลบคำที่ไม่มีความหมาย ฯลฯ)

การฝึกโมเดล Machine Learning เพื่อจำแนกอารมณ์ความรู้สึก

การประเมินประสิทธิภาพของโมเดลด้วยค่าชี้วัดต่าง ๆ

การแสดงผลการวิเคราะห์อารมณ์ด้วยกราฟและภาพสถิติ

เทคโนโลยีที่ใช้

Python

TensorFlow / PyTorch (ขึ้นอยู่กับการใช้งาน)

scikit-learn

Hugging Face datasets

Pandas, NumPy, Matplotlib

วิธีติดตั้ง

# โคลนโปรเจกต์จาก GitHub
git clone <repository_url>
cd <repository_name>

# ติดตั้งแพ็กเกจที่จำเป็น
pip install -r requirements.txt

วิธีใช้งาน

# วิเคราะห์อารมณ์จากข้อความตัวอย่าง
python predict.py --text "บริการดีมากครับ ชอบมาก"

ชุดข้อมูลที่ใช้

ชุดข้อมูลที่ใช้ในโปรเจกต์นี้คือ wisesight_sentiment ซึ่งสามารถเข้าถึงได้จาก Hugging Face:
https://huggingface.co/datasets/wisesight_sentiment

การมีส่วนร่วม

โปรเจกต์นี้จัดทำขึ้นเพื่อการศึกษา หากต้องการมีส่วนร่วมสามารถช่วยปรับปรุงขั้นตอนการเตรียมข้อมูล เพิ่มประสิทธิภาพของโมเดล หรือพัฒนาให้รองรับคุณสมบัติใหม่ ๆ ได้

สัญญาอนุญาต

โปรเจกต์นี้อยู่ภายใต้สัญญาอนุญาตแบบ MIT License

