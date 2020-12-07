totalprice = int(input("Price : "))


def vatCalculate(totalprice):

    result = totalprice+(totalprice * 7/100)
    
    return result
    

print(vatCalculate(100))
