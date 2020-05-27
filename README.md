# Text-relevance
https://drive.google.com/drive/folders/1DCCsGvyBfv0DSLmqnif7wNCAL3Zy7xHJ
new_bert_score.txt, bert_score1.txt, bert_score2.txt, bert_score3.txt are bert cosine similarity of passages to query divided in pieces, 
which are then concatenated into one inside the script.
(it takes long time to calculate so creating 1 file would be unsafe if the process crashes)
bert_docs.txt are docs parsed in the way which is best for bert(basically just text)
bm_docs.txt are docs parsed in the way which is best for bm(lematization, some synonims, e.t.c)
