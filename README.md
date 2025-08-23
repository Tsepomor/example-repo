swimming =  int(input("Please enter your time for swimming: "))
cycling =  int(input("Please enter your time for cycling: "))
running =  int(input("Please enter your time for running: "))

triathlon_total = swimming + cycling + running

print("Total time taken for the triathlon: " + str(triathlon_total) )

if triathlon_total > 0 and triathlon_total < 100:
    print("Award: Provincial colours")
elif triathlon_total > 101 and triathlon_total < 105:
    print("Award: Provincial half colours")
elif triathlon_total > 106 and triathlon_total < 110:
    print("Award: Provincial scroll")
else:
    print("No award")
