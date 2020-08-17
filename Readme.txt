1. DESCRIPTION
--------------

The SMS Spam Collection, the database of real sms spams from uci machine learning repository is used. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. 


1.1. Statistics
---------------

There is one collection:

The SMS Spam Collection has a total of 4,827 SMS legitimate messages and a total of 747 spam messages.


1.2. Format
-----------

The files contain one message per line. Each line is composed by two columns: one with label (ham or spam) and other with the raw text. Here are some examples:

ham	Go until jurong point, crazy.. Available only in bugis n great world la e buffet... Cine there got amore wat...
ham	Ok lar... Joking wif u oni...
spam	Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005. Text FA to 87121 to receive entry question(std txt rate)T&C's apply 08452810075over18's
ham	U dun say so early hor... U c already then say...
ham	Nah I don't think he goes to usf, he lives around here though
spam	FreeMsg Hey there darling it's been 3 week's now and no word back! I'd like some fun you up for it still? Tb ok! XxX std chgs to send, £1.50 to rcv
ham	Even my brother is not like to speak with me. They treat me like aids patent.
ham	As per your request 'Melle Melle (Oru Minnaminunginte Nurungu Vettam)' has been set as your callertune for all Callers. Press *9 to copy your friends Callertune
spam	WINNER!! As a valued network customer you have been selected to receivea £900 prize reward! To claim call 09061701461. Claim code KL341. Valid 12 hours only.
spam	Had your mobile 11 months or more? U R entitled to Update to the latest colour mobiles with camera for Free! Call The Mobile Update Co FREE on 08002986030
ham	I'm gonna be home soon and i don't want to talk about this stuff anymore tonight, k? I've cried enough today.
spam	SIX chances to win CASH! From 100 to 20,000 pounds txt> CSH11 and send to 87575. Cost 150p/day, 6days, 16+ TsandCs apply Reply HL 4 info
spam	URGENT! You have won a 1 week FREE membership in our £100,000 Prize Jackpot! Txt the word: CLAIM to No: 81010 T&C www.dbuk.net LCCLTD POBOX 4403LDNW1A7RW18
ham	I've been searching for the right words to thank you for this breather. I promise i wont take your help for granted and will fulfil my promise. You have been wonderful and a blessing at all times.
ham	I HAVE A DATE ON SUNDAY WITH WILL!!
spam	XXXMobileMovieClub: To use your credit, click the WAP link in the next txt message or click here>> http://wap. xxxmobilemovieclub.com?n=QJKGIGHJJGCBL



2. USAGE
--------
2.1. 
python execution:
 
The main dataset SMSSpamCollection.xlsx and a new excel sheet to write data given as new.xlsx are given. Make sure that these two files are in the same folder.
Then execute the given python file to get the newcsv1.csv, newcsv2.csv and the final arff file as final_arff.arff

2.2.
weka execution

In the weka, choose 'Explorer' in the 'Applications' menu.
Then a pop up box is opened. Select open file in preprocess menu and select the file from the path which you gave.
Then goto classify and choose the following different classifiers
a)Decision Tree (J48)
b)Multinomial Naive Bayes
c)K-Nearest Neighbors
d)SVM (LibSVM)
e)RandomForest










