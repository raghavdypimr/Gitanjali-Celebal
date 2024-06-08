for i in range(s)
if string(i) in 'AIEOU':
    vow=vow*(s-i)
    else:  
        con=con*(s-i)
        
if con>vow:
    print('stuart {} '.format(con))
elif con=vow:
    print{'Draw'}
else:
    print{'kevin {}'. format(vow)}
