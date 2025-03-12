- [x] def years_taon(age):
    
    if age < 0:
        print("ayaw naman! wag ka kasi mag enter ng negative age.")
    
    elif age <= 10:
        print("BATA KA PA, CHILD.")
    elif age <= 18:
        print("BINATA KA NA, TEEN.")
    elif age <= 60:
        print("PATANDA KA NA, ADULT.")
    else:
        print("TANDA MO NA, SENIOR.")


print("Welcome sa age checker na kung saan malalaman mo dito kung anong uri ka na ng tanda")

while True:
    try:
        
        glenn = input("Ilang taon ka naman ba bes? : ")
        
        years_taon(int(karl))
    except ValueError:
        print("ayaw lumabas kasi may decimal point!.")
