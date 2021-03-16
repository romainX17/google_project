# google_project
 
## How to use 

The pretrained model is not avaiblable here as it is too big for Github,  
You will be able to access the complementary files in this address: https://drive.google.com/file/d/1tgOIOFZi0Nr5smLR7zZLZisoXBAMK5vh/view?usp=sharing

You can also train on local, for this in the GRIT.ipynb change:  
%run "run_pl_s_t.py" --data_dir ../../Data --model_type bert --model_name_or_path bert-base-uncased --n_gpu 1 --output_dir output --max_seq_length_src 32 --max_seq_length_tgt 32 --num_train_epochs 7 --train_batch_size 32 --eval_batch_size 1  
you will add --do train

You may have to reduce --train_batch_size 32 depending on your VRAM  

For simple use unzip the file and add the complementary files then run every cell one by one of GRIT.ipynb until S.main() is executed you will be able to run the chatbot and play with him 


## Info

The grit model is a modified version adapted to our data from https://github.com/xinyadu/grit_doc_event_entity, most of the model's credit is due to its original authors
