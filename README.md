import pandas as pd

# Đọc dữ liệu từ các sheet và ghép lại thành một DataFrame
df = pd.concat(pd.read_excel('data.xlsx', sheet_name=['Sheet1', 'Sheet2', 'Sheet3']), ignore_index=True)

# In kết quả
print(df)
