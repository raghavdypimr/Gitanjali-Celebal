def print_formatted(number):
    # your code goes here
    l=len("{0:b)".format(number))
    
    for i in range(1,number+1):
        print("{0:{w}d} {0:{w}o} {0:{w}x} {o:{w}b}" .format(i,w=1})
    

if __name__ == '__main__':
