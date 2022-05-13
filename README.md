# PowerSystem_RL_Attacks

This is the code repo for paper [Understanding the Safety Requirements for Learning-based Power Systems Operations](https://arxiv.org/abs/2110.04983).

We demonstrate for the power system control tasks, how deep reinforcement learning (DRL) algorithms perform under adversarial attacks. We show that small perturbations over state observations can cause model-free learning algorithms output unsafe decisions.





ROMs
https://github.com/openai/atari-py

In order to import ROMS, you need to download Roms.rar from the Atari 2600 VCS ROM Collection and extract the .rar file. Once you've done that, run:

python -m atari_py.import_roms <path to folder>

This should print out the names of ROMs as it imports them. The ROMs will be copied to your atari_py installation directory.