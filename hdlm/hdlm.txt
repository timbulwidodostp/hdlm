# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fitting High Dimensional Linear Models Use hdlm With (In) R Software
install.packages("remotes")
remotes::install_github("cran/hdlm")
library("hdlm")
hdlm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/hdlm/main/hdlm/hdlm.csv",sep = ";")
# Estimation Fitting High Dimensional Linear Models Use hdlm With (In) R Software
x <- cbind(hdlm$hdlm_1, hdlm$hdlm_2, hdlm$hdlm_3)
y <- hdlm$hdlm
hdlm <- hdlm(y ~ x)
summary(hdlm)
# Fitting High Dimensional Linear Models Use hdlm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished