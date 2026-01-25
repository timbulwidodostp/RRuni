# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Univariate analysis of randomized response data Use RRuni (RRreg) With (In) R Software
install.packages("RRreg")
library("RRreg")
# Estimate Univariate analysis of randomized response data Use RRuni (RRreg) With (In) R Software
RRuni = read.csv("https://raw.githubusercontent.com/timbulwidodostp/RRuni/main/RRuni/RRuni.csv", sep = ";")
RRuni <- RRuni(response = response, data = RRuni, model = "Warner", p = 0)
summary(RRuni)
# Univariate analysis of randomized response data Use RRuni (RRreg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished