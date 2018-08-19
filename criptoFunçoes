A = ["A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P", "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z"]

def cripta(x):
    L = []
    G = []
    msg = ""
    for k in x:
        for l in range(0, len(A)):
            if k == A[l]:
                L.append(l)
                
    for k in range(0, len(A)):
        if A[k] == A[-1]:
            G.insert(0, A[k])
        else:
            G.insert(k+1, A[k])
            
    for k in range(0, len(L)):
        L[k] = G[L[k]]
        msg = msg + str(L[k])
    print msg


def decripta(x):
    L = []
    G = []
    msg = ""
    for k in x:
        for l in range(0, len(A)):
            if k == A[l]:
                L.append(l)
    
    for k in range(0, len(A)):
        if A[k] == A[0]:
            G.insert(0, A[k])
        else:
            G.insert(k-1, A[k])

    for k in range(0, len(L)):
        L[k] = G[L[k]]
        msg = msg + str(L[k])
    print msg



def converte(x):
    x = x.upper()
    msg = ""

    Let = ["A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P", "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z"]
    Num = ["10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "32", "33", "34", "35"]
    
    print "Sua mensagem:", x

    for k in x:
        for l in range(0, len(Let)):
            if k == Let[l]:
                msg += str(Num[l])
        
    print "Sua mensagem convertida:", msg

def desconverte(x):
    msgList = []
    msg = ""
    
    Let = ["A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P", "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z"]
    Num = ["10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23", "24", "25", "26", "27", "28", "29", "30", "31", "32", "33", "34", "35"]
    
    print "Sua mensagem convertida:", x

    for k in str(x):
        msgList.append(k)

    for k in range(0, len(msgList), 2):
        for l in range(0, len(Let)):
            if msgList[k] + msgList[k + 1] == Num[l]:
                msg += str(Let[l])

    print "Sua mensagem:", msg.upper()
