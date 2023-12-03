# RL_recommendation
RL_recommendation

## Frontend

## Backend
### Env

* select a random image at beginning and compare similarity with options and the target
* embedding model (Autoencoder to compare image)
   * 
* interface to construct state for historical choice, current choice and reward
* State:
  * current option: (length_embedding)
  * current choice: (1,)
  * reward

### Model
* Imagedataset - load images and their embedding
* memory - for model replay.
* agent - PPO(policy, criticNet)
