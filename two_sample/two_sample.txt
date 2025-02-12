# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fast Permutation Based Two Sample Tests Use two_sample (twosamples) With (In) R Software
install.packages("twosamples")
library("twosamples")
two_sample = read.csv("https://raw.githubusercontent.com/timbulwidodostp/two_sample/main/two_sample/two_sample.csv",sep = ";")
# Estimation Fast Permutation Based Two Sample Tests Use two_sample (twosamples) With (In) R Software
two_sample_1 = two_sample$two_sample_1
two_sample_2 = two_sample$two_sample_2
two_sample = two_sample(two_sample_1, two_sample_2)
summary(two_sample)

plot(two_sample)
# Fast Permutation Based Two Sample Tests Use two_sample (twosamples) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished