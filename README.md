# MME
MME: Mitigating the Impact of Malware Evolution on API Sequence-based Windows Malware Detectors

Dataset URL: https://pan.baidu.com/s/1x9IzfgujqSx4vywWjwBsOQ?pwd=1111  Extract Code：1111

contact email:talentedyuan@gmail.com

# About the Dataset
Training Dataset：
- 2017_data.npz: Training set of embeddings for the original model
- Evolve_2017_data: Training set of embeddings for the enhanced model

Testing Dataset：
The embedding test set of the original model：
- final_2018_data.npz
- final_2019_data.npz
- final_2020_data.npz
- final_2021_data.npz

embedding test set of the enhanced model：
- final_evolve_2018_data.npz
- final_evolve_2019_data.npz
- final_evolve_2020_data.npz
- final_evolve_2021_data.npz

# How to read: 
train_data = np.load('./data/Evolve_2017_data.npz')

train_x = train_data['x']

train_y = train_data['y']

train_y_family = train_data['y_family']


train_data = np.load('./data/2017_data.npz')

train_x = train_data['x']

train_y = train_data['y']

