# Fahrenheit-to-Celsius

temperatures = [10,-20,-289,100]

def c_to_f(c):
    if c > -273.15:
        f = (c * 9/5) + 32
        return f
    else:
        return "Pretty sure that is too cold for earth."

for temp in temperatures:
    print(c_to_f(temp))
