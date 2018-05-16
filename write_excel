from openpyxl import Workbook,load_workbook

wb = load_workbook('1.xlsx')
ws = wb.active
for a, i in enumerate(list(ws.rows)):
    if a > 1146:
        print(i[18].value)
wb.save('1.xlsx')

# wb = Workbook()
# ws = wb.active
# ws.cell(row=row, column=1).value = album.upc
# wb.save('2.xlsx')
