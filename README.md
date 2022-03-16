# mean
x<-scan()
m=0
n=length(x)
for(i in 1:n)
{
    m=m+x[i]
}
mean=m/n
n=length(x)
for(i in 1:n)
{
sprintf("mean is %f",mean)
