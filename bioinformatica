f = open("Bioinf/rosalind_dna.txt", "r")
seq = f.readline().rstrip()
f.close()

nucleotides = {"A":0, "C":0, "G":0, "T":0}

for c in seq:
    nucleotides[c] = nucleotides[c] + 1

result = " ".join(str(value) for value in nucleotides.values())
print (result)

#####

seq = "GATATATGCATATACTT"
find = "ATAT"
dist = len(find)
pos = []

for i in range (0, len(seq)-dist):
    curr = seq[i:i+dist]
    
    if curr == find:
        pos.append(i+1) # solution uses 1-based numbering

# printing the list using * operator separated by space  
print(*pos)
