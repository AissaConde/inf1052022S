#Importation de donnees#
df<-read.csv("Creditbancaire.csv")

#Explorer l'objet#
str(df)

#la moyenne du credit#
mean(df$Credit)

#La moyenne du nombre de jour de retard de paiement#
res.by<-by(df$Jours, df$Type,mean )
res.by

#La representation graphique#
A<-res.by
barplot(A)
