# python_amaliyot_2
Python lug'at, nesting lug'atlar va funcsiyalarga doir dasturlar

oila={'otam':{'ism':'jontemir','yosh':45,'t_joy':'qashqadaryo'},
      'onam':{'ism':'gulzoda','yosh':37,'t_joy':'qashqadaryo'},
      'kata_ukam':{'ism':'javlon','yosh':16,'t_joy':"farg\'ona"},
      'kichkina_ukam':{'ism':'ibrohim','yosh':10,'t_joy':'samarqand'},
      'men':{"ism":'mavlon','yosh':19,'t_joy':'qashqadaryo'}}
for key , value in oila.items():
    if key!='men':
        print(f"{key}ning ismi {value['ism'].title ()} , yoshi {value['yosh']} da , "
              f"{value['t_joy'].capitalize()} viloyatida tug'ilgan")
    if key=='men':
        print(f"{key}ing ismim {value['ism'].title()} , yoshim {value['yosh']} da ,"
              f"{value['t_joy'].capitalize()} viloyatida tug'ilganman")

taomlar={'dadam':'tandir','ayam':'dimlama','javlon':'tabaka',
         'ibrohim':'shashlik','men':'farqi_yo\'q'}
for ism , taom in taomlar.items():
    if ism=='men':
        print(f"{ism.title()}ga qanday ovqat bo'lsayam {taom}")
    else:
        print(f"{ism.title()}ning yaxshi ko'rgan taomi {taom}")
        
lugat={'if':'agar','else':'aks holda','integer':'butun sonlar','float':'haqiqiy sonlar',
       'del':'o\'chirish','remove':'o\'chirish','get':'xatolikni oldini olish',
       'upper':'katta harflar','title':'har bir so\'z katta harfda','capitalize':'faqat birinchi_harf_katta',
       'string':'matn'}
print("Pythonning izohli lug'ati:")
for key , value in lugat.items():
    print(f"{key}-{value}")
    
lugat={'if':'agar','else':'aks holda','integer':'butun sonlar','float':'haqiqiy sonlar',
       'del':'o\'chirish','remove':'o\'chirish','get':'xatolikni oldini olish',
       'upper':'katta harflar','title':'har bir so\'z katta harfda','capitalize':'faqat birinchi_harf_katta',
       'string':'matn'}
suz=input("Biron bir so'z kiriting : ")
key , value=lugat.items()
if suz==key:
    print(f"{suz} ning ma'nosi {value}")
else:
    print(f"Lug'atda {suz} so'zining tarjimasi yo'q")
