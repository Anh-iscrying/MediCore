# 🏥 MediCore - Hệ thống Số hóa Hồ sơ Y tế & Quản lý Điều trị thông minh

MediCore là giải pháp số hóa quy trình tương tác giữa Bác sĩ và Bệnh nhân, tập trung vào việc quản lý hồ sơ bệnh án điện tử (EMR) trọn đời và tối ưu hóa vận hành phòng khám bằng trí tuệ nhân tạo (AI).

## 🚀 Điểm sáng dự án (Key Features)

🆔 Hệ thống định danh kép: Tách biệt patient_code (trọn đời) và emr_code (theo ca khám) để quản lý lịch sử y tế xuyên suốt.

🤖 Trợ lý AI: Tự động gợi ý chuyên khoa cho bệnh nhân và tóm tắt bệnh sử, sinh lời dặn y khoa cho bác sĩ.

⚡ Hàng chờ Real-time: Cập nhật trạng thái gọi số và điều phối ca khám tức thời qua WebSocket.

📄 E-Prescription: Tự động xuất bản đơn thuốc và kết quả khám định dạng PDF chuyên nghiệp.

🛡️ Bảo mật chuyên sâu: Xác thực tập trung với JWT và cơ chế chống spam tài khoản qua Số điện thoại.

## 🛠 Tech Stack
- Backend: Python 3.10+, FastAPI (Asynchronous framework).
- Frontend: React.js, Ant Design (UI Kit), Tailwind CSS.
- Database: PostgreSQL (Relational Data), SQLAlchemy (ORM).
- Real-time: WebSocket (STOMP/Websock-client).
- AI Integration: OpenAI API / Gemini API (LangChain).

## 📁 Cấu trúc thư mục (Project Structure)
```bash
MediCore-Project/
├── docs/               # Tài liệu đặc tả SRS, ERD và Backlog
├── code/
│   ├── backend/        # FastAPI Source Code
│   └── frontend/       # React.js Source Code
├── .agent/             # AI Workflow & Rules
└── tests/              # Unit & Integration Tests
```

## 🛠 Hướng dẫn cài đặt (Quick Start)

1. Backend (Python/FastAPI)
```bash
cd code/backend
python -m venv venv
source venv/bin/activate  # Windows: .\venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```
Truy cập Swagger UI tại: http://localhost:8000/docs

2. Frontend (React.js)
```bash
cd code/frontend
npm install
npm run dev
```
Truy cập ứng dụng tại: http://localhost:5173

## 👥 Đội ngũ thực hiện (Team)
- Thành viên A (Leader): Backend Architecture, Security & Database.
- Thành viên B: Business Logic, AI Integration & PDF Service.
- Thành viên C: Frontend Patient Portal & UI/UX.
- Thành viên D: Frontend Doctor Dashboard & WebSocket.

### Dự án được thực hiện trong vòng 4 tuần theo mô hình Agile-Scrum.
