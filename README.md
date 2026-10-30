# System Design Laboratory

Repo ฝึก System Design 12 สัปดาห์ (2026-10-29 ถึง 2027-01-20) แยกจากงานประจำ
ใช้โดเมนเดียวตลอด: chain ร้านขายยา 1,000 สาขา ที่ต้องจัดการ stock ยาร่วมกัน

Checklist รายสัปดาห์: [สมุดฝึก System Design](https://claude.ai/artifact/SPpy3Rwy74KfPfe4fb4niV)

## กติกา

1. เขียน design ของตัวเองให้เสร็จก่อน แล้วค่อยให้ AI critique ห้ามให้ AI ออกแบบให้ตั้งแต่แรก
2. อ่านทฤษฎีแล้วให้ AI ตั้งคำถามทดสอบ ไม่ใช่ให้มันอธิบาย
3. Mock จับเวลา 45 นาที ไม่เปิด AI

## โครงสร้าง

```
docs/   design doc และ mock หนึ่งไฟล์ต่อหนึ่งสัปดาห์: wNN-ชื่อโจทย์.md
labs/   การทดลองด้วย docker compose เดือนละครั้ง: wNN-ชื่อการทดลอง/
```

- เริ่ม design doc หรือ mock ใหม่: คัดลอก [`docs/_template.md`](docs/_template.md)
- เริ่มการทดลองใหม่: ดู [`labs/README.md`](labs/README.md)
