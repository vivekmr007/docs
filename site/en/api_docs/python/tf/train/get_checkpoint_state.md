


<!-- DO NOT EDIT! Automatically generated file. -->
# tf.train.get_checkpoint_state

### `tf.train.get_checkpoint_state`

```
tf.train.get_checkpoint_state(checkpoint_dir, latest_filename=None)
```


See the guide: [Variables > Saving and Restoring Variables](../../../../api_guides/python/state_ops#Saving_and_Restoring_Variables)

Returns CheckpointState proto from the "checkpoint" file.

If the "checkpoint" file contains a valid CheckpointState
proto, returns it.

#### Args:

* <b>`checkpoint_dir`</b>: The directory of checkpoints.
* <b>`latest_filename`</b>: Optional name of the checkpoint file.  Default to
    'checkpoint'.


#### Returns:

  A CheckpointState if the state was available, None
  otherwise.


#### Raises:

* <b>`ValueError`</b>: if the checkpoint read doesn't have model_checkpoint_path set.

Defined in [`tensorflow/python/training/saver.py`](https://www.tensorflow.org/code/tensorflow/python/training/saver.py).
