# Exercise3

to do: 
- change model for deepfool, deepfool works better without softmax activation (output needs to be made of logits)
- try defensive distillation (https://chatgpt.com/share/5d6eecb0-2d9e-457c-9d22-f0d33416ea09) 
- run adversarial training 
    - with existing implementation art toolbox
    - making attack on x_train and then take 50% benign x_train and 50% adv x_train to train model
- maybe another attack from slides, ifgs/jsma/cw, and then universal perturbation based on that attacker (running deepfool takes so long for making universal perturbation - 5hrs on t4)
- play around with visualizations and how report would look like (maybe we need more plots, add std to distortion metrics etc)

