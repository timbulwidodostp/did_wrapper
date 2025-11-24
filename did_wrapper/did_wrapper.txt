# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# A Multi-Method Difference-in-Differences Estimator Use did_wrapper (fect) With (In) R Software
install.packages("fect")
library("fect")
did_wrapper = read.csv("https://raw.githubusercontent.com/timbulwidodostp/did_wrapper/main/did_wrapper/did_wrapper.csv",sep = ";")
# Estimation ARFIMA (Autoregressive Fractionally Integrated Moving Average) Use arfima With (In) R Software
did_wrapper <- did_wrapper(data = did_wrapper, Y = "nat_rate_ord", D = "indirect", index = c("bfs", "year"), method = "twfe")
did_wrapper$est.avg
did_wrapper$est.att
# A Multi-Method Difference-in-Differences Estimator Use did_wrapper (fect) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished