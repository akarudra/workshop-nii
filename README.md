# workshop-nii


```{R Basics}
hello <- function(){
  print('Hello World')
}


 > my_fav_variable
Error: object 'my_fav_variable' not found
> my_fav_variable <- c('IL6','LINC','OAS1')
> my_fav_variable
[1] "IL6"  "LINC" "OAS1"
> #Its working fine

> #Antigen processing and presentation - Homo sapiens (human)
> 
> pathway_hsa04612<- c('ifng','tnf','pmse1','pmse2','pmse3','pmse4','hp1s','hsp90a','mhc1','canx','b2m','pdia3','calr','tapbp','abcb2','abcb3','cd8a','cd8b','trav','trbv')
> entry_number<-c('ko4687','ko3156','KO6696','KO6697','KO3283','KO9489','KO4079','KO6751','KO8054','KO8055','KO8056','KO8056','KO8057','KO8058','KO5653','KO5654','KO648','KO6459','K10784','K1078')
> index<-data.frame(pathway_hsa04612,entry_number)


#composition of dataframe with one charector vector and one numeric vector
 names<-c('jb','varun','anshul')
> hight<-c('5.5','5.7','6')
> index<-data.frame(names,hight)
> index
   names hight
1     jb   5.5
2  varun   5.7
3 anshul     6
> rbind(index,new=c('athar',5.9))
   names hight
1     jb   5.5
2  varun   5.7
3 anshul     6
4  athar   5.9
> index<-rbind(index,new=c('athar',5.9))
> index
   names hight
1     jb   5.5
2  varun   5.7
3 anshul     6
4  athar   5.9
> cbind(index,lab=c('moil','sfbl','lii','iil'))
   names hight  lab
1     jb   5.5 moil
2  varun   5.7 sfbl
3 anshul     6  lii
4  athar   5.9  iil
> index<-cbind(index,lab=c('moil','sfbl','lii','iil'))
> index
   names hight  lab
1     jb   5.5 moil
2  varun   5.7 sfbl
3 anshul     6  lii
4  athar   5.9  iil
> 

```
