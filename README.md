# Facial features alignment

This is the Face alignment task of module Computer vision at University of Sussex.

This task build the CNN model that can predict the facial feature on people's face and able to apply Virtual Make-up based on the feature that model predicted.

## Dataset
In this dataset, each data point consists 42 points in each image (people's face).

The Template:
<p align="center">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/f290a3bd-34be-4901-a108-f9195b4acdd9.png" alt="Graph Description">
</p>

In training set, there 2811 images (faces) with size (244, 244), each image come with 42 facial feature points and testing set on has the images without facial feature points.
The goal is to predict the facial feature points of test set by the model trained on training set.

Examples on training set:
<p align="center">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/1c86db83-b241-4cdb-963e-dd39deb32cfd.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/6e59b585-cdbe-443e-a5e9-361ea6c455db.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/eaffca22-5386-48c0-bc22-bf37688e091a.png">
</p>

## Result on test set:
<p align="center">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/20f7b852-f58d-4bbe-903a-9c5308e01799.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/f5ddc232-2246-4dbb-ad91-387caacbd7f7.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/e256aa29-4132-42cc-a2c3-bd3f31106798.png">
</p>

## Apply Virtual Make-up:

lipstick:
<p align="center">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/23b07170-c918-47f9-82d5-60abf27bb58f.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/4e6cf05a-68bc-42b4-b6d5-700bf377e82e.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/40f0b99c-c641-48fb-acab-f6905eab0de5.png">
</p>

Result:
<p align="center">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/6fe7b678-bbd0-4081-9950-942693650e63.png">
</p>

More example:
<p align="center">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/f30ef82f-6525-4675-a0de-f30fc1d7b606.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/3869158d-42da-4cf8-8976-bb902819757e.png">
  <img src="https://github.com/Turkeywobbling/Face-alignment/assets/105172948/dd2150a9-5472-49cd-9462-897392186746.png">
</p>


