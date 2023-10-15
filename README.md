# simple_meson_project

1: setup python virtual environment and install meson

python3.10 -m venv meson_venv

source ../meson_venv/bin/activate

pip install meson

2: clone simple project

git clone  git@github.com:abbasraza/simple_meson_project.git

cd simple_meson_project/example1

3: meson setup (to create ninja build file)

meson setup build

4: build and run simple project

cd build/

ninja 

./hello_meson

