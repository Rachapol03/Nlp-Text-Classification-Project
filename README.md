# Nlp-Text-Classification-Project
NLPProject : Preprocessing Code {Vscode} ถ้าจะ Run fix path ก่อน
Project_Class_Data : Dataset [154726 rows x 2 columns]

text : ข้อความ N-gram[1,4] 
word_tokenize : pythainlp

labels : s = ใต้
	n = เหนือ
	m = กลาง
	e = อีสาน

concat : south_df [24755 rows × 1 columns]
	mid_df [87128 rows × 1 columns]
	north_df [38649 rows × 1 columns]
	esan_df [28339 rows × 1 columns]

clean : ลบคำที่ไม่ใช่ [ก-๙\s]
	ลบคำซ้ำ
