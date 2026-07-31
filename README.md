# 0730-B-HSR-APE-

with open(FINAL_JSON_PATH, "r", encoding="utf-8") as f:
    q = json.load(f)

print("HSR生データ内 Remark 2:", q["raw_remark_2_rows"])
print("最終採用 Remark 2:", q["accepted_remark_2_rows"])
