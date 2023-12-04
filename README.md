# Git_Hard_DZ

Ура домашнее задание

вставить в проект ниже изложенный код


int[] FillArray(int size, int min, int max) 
{
    int[] filledArray = new int[size];
    for (int i = 0; i < filledArray.Length; i++){
        filledArray[i] = new Random().Next(min, max + 1);
    }
    return filledArray;
}