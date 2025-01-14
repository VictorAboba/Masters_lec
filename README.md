# Лекционный материал для магистров УРФУ
Установка tensorflow на windows с поддержкой GPU (простой способ):
1. Скачать Anaconda по ссылке: https://www.anaconda.com/download/success
2. Открыть терминал в Anaconda Navigator (Anaconda Navigator -> anaconda_promt)
3. В терминале прописываем команду: conda install python=3.10
4. После загрузки прописываем команды: <br>
   conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0 <br>
   python -m pip install "tensorflow<2.11"
5. Запустить Jupyter Notebook (откроется файловая система компьютера, где можно найти и запустить любой файл формата .ipynb)
6. Проверить доступность GPU можно, выполнив первый блок в Jupyter Notebook из первой лекции (Если нет, то ничего страшного, код будет работать, но медленнее) 
