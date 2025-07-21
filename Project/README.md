# Chatbot Fine-tuning with Direct Preference Optimization (DPO)

## 📌 Giới thiệu
Dự án này tập trung vào việc **fine-tuning mô hình chatbot** sử dụng phương pháp **Direct Preference Optimization (DPO)** nhằm nâng cao chất lượng phản hồi dựa trên sở thích của người dùng.  
Base model sử dụng: **EleutherAI/pythia-70m**  
Kỹ thuật tối ưu: **LoRA (Low-Rank Adaptation)** để giảm chi phí huấn luyện.

---

## 🚀 Tính năng chính
- **Fine-tuning với DPO** để tối ưu phản hồi của chatbot.
- **Sử dụng dữ liệu cặp Chosen/Rejected** để học preference.
- **Theo dõi Training Loss, Validation Loss, Reward Margin và Accuracy**.
- **LoRA PEFT** giúp huấn luyện nhanh, tiết kiệm bộ nhớ.
