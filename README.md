# chromedriverdownloader


https://stackoverflow.com/questions/72474704/how-to-count-the-uppercase-and-lowercase-letters-in-string-writing-lesser-code

lower_count = len([i for i in str1.replace(' ','') if i.islower()])
print(lower_count, '\t', len(str1.replace(' ','')) - lower_count)
