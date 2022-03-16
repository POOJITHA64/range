# range
print("enter data")
x<-scan()
n<-length(x)
big=x[1]
small=x[1]
for(i in 1:n)
{
  if(x[i]>big){
    big=x[i]
  }
}
for(i in 1:n)
{
  if(x[i]<small){
    small=x[i]
  }
}
sprintf("big is %d",big)
sprintf("small is %d",small)
range=big-small
sprintf("range is %d",range)

