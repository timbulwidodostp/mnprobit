# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Multinomial probit model Use mnprobit With (In) R Software
install.packages("switchSelection")
library("switchSelection")
mnprobit = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mnprobit/main/mnprobit/mnprobit.csv",sep = ";")
# Estimation Multinomial probit model Use mnprobit With (In) R Software
f_mnprobit <- Dependen ~ Independen_1 + Independen_2 + Independen_3
mnprobit <- mnprobit(f_mnprobit, data = mnprobit)
summary(mnprobit)
# Multinomial probit model Use mnprobit With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished