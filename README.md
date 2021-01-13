text = "X-DSPAM-Confidence:    0.8475"
value=text.find(':')
n_val=text[value+1:]
f_val=float(n_val)
print(f_val)
