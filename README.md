# google_project
 
## How to use 

The pretrained model is not avaiblable here as it is too big for Github, 
You will be able to access the complementary files in this address

You can aslo train on local for this in the GRIT.ipynb change:
%run "run_pl_s_t.py" --data_dir ../../Data --model_type bert --model_name_or_path bert-base-uncased --n_gpu 1 --output_dir output --max_seq_length_src 32 --max_seq_length_tgt 32 --num_train_epochs 7 --train_batch_size 32 --eval_batch_size 1
you will add --do train
