labels <- c("总人数", "女生", "男生")
counts <- c(58, 17, 41)
png(paste0("你的名字+条形图.png"))
barplot(counts, names.arg = labels, main = "大数据班人数", 
    xlab = "", ylab = "人数")
dev.off()
