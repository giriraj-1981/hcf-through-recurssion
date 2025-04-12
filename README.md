# hcf-through-recurssion
def compute_hcf(x,y):
    while y%x!=0:
        r=y%x
        y=x
        x=r

    return x

hcf=compute_hcf(300,400)
print("the h c f is:",hcf)
