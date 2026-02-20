# 1
mkdir tpLinux

# 2
tree

# 3
cd ./tpLinux
touch {fic1,fic2,exoos}.txt
touch {fichier,exos}.md
touch image.jpeg

# 4
mkdir {dosA,dosB}
mkdir ./dosA/{dosB,dosC}
tree

# 5
mv ./fi* ./dosA/dosB

# 6
./dosA/dosB
cp ./fic1.txt ../
cp ./fic2.txt .././dosC
cp ./fichier.md ../.././dosD

# 7
cd ../../
echo -e "bonjour tout le monde" > fic1.txt
ls -lh ./fic1.txt

# 8
ls -l ./*.???

# 9
mv ./exoos.txt ./exos.txt

# 10
cd ../
touch ./supprimer.sh
echo -e "rm -r ./tpLinux" > ./supprimer.sh
chmod u+x ./supprimer.sh
./supprimer.sh