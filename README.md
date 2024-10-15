# Visqol

Forked from https://github.com/google/visqol

# install
```bash
sudo apt install apt-transport-https curl gnupg -y
curl -fsSL https://bazel.build/bazel-release.pub.gpg | gpg --dearmor >bazel-archive-keyring.gpg
sudo mv bazel-archive-keyring.gpg /usr/share/keyrings
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/bazel-archive-keyring.gpg] https://storage.googleapis.com/bazel-apt stable jdk1.8" | sudo tee /etc/apt/sources.list.d/bazel.list

sudo apt update && sudo apt install bazel-5.1.0
sudo ln -s /usr/bin/bazel-5.1.0 /usr/bin/bazel
bazel --version

pip install git+https://github.com/pengzhiliang/visqol.git
```
