# Xóa các dòng trùng lặp và trộn dữ liệu
df_merged = df_merged.drop_duplicates().sample(frac=1).reset_index(drop=True)
