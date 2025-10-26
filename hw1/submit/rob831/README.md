## Run the code

### Section 1 (Behavior Cloning)
General command for section 1:

To generate the numbers in Table 1 in jupyter notebook, set the hyperparameters(default) as followings, then set the environment name with Ant-v2, Humanoid-v2, Walker2d-v2,
Hopper-v2 and HalfCheetah-v2:
ep_len= 1000, num_agent_train_steps_per_iter= 1000, n_iter = 1, batch_size=
1000, eval_batch_size= 2000, train_batch_size= 100, max_replay_buffer_size=1000000, n_layers= 5,
learning_rate= 5e-3

General command for section 2:

To generate Table 2 in jupyter notebook, set the hyperparameters as follow for Ant-v2 and Hopper-v2:
ep_len= 1000, num_agent_train_steps_per_iter= 1200, n_iter = 1, batch_size=
1000, eval_batch_size= 2000, train_batch_size= 100, max_replay_buffer_size=1000000, n_layers= 5,
learning_rate= 4e-3

General command for section 3:

To generate figure 1 in jupyter notebook, set the hyperparameters as follow with num_agent_train_steps_per_iter as 1000, 1300, 1600, 1900, 2200 for Ant-v2:
ep_len= 1000, num_agent_train_steps_per_iter= 1200, n_iter = 1, batch_size=
1000, eval_batch_size= 2000, train_batch_size= 100, max_replay_buffer_size=1000000, n_layers= 5,
learning_rate= 4e-3

Make sure to follow the homework PDF for more details on what else you need to run.
To generate videos of the policy, remove the `--video_log_freq -1` flag.

### Section 2 (DAgger)
General command for section 2:
(Note the `--do_dagger` flag, and the 8 for `n_iter`)

General command for section 1:

To generate the numbers in figure 2 in jupyter notebook, set the hyperparameters as followings, then set the environment name with Ant-v2 and Hopper-v2:
ep_len= 1000, num_agent_train_steps_per_iter= 1200, n_iter = 8, batch_size= 1000, eval_batch_size= 2000,
train_batch_size= 100, max_replay_buffer_size=1000000, n_layers= 3, learning_rate= 4e-3, do_dagger = True
