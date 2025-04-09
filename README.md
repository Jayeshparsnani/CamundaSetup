Following repo contain the application files which will be used to run the Camunda Server.
Please follow the following steps:
1. Download the elasticsearch8.11.1 according to your system : https://www.elastic.co/downloads/past-releases/elasticsearch-8-11-1
2. Download tasklist8.5.11 : https://github.com/camunda/camunda-platform/releases/download/8.5%2Bgen14/camunda-tasklist-8.5.11.zip
3. Download zeebe8.5.13 : https://github.com/camunda/camunda-platform/releases/download/8.5%2Bgen16/camunda-zeebe-8.5.13.zip
4. Download operate8.5.6 : https://github.com/camunda/camunda-platform/releases/download/8.5%2Bgen9/camunda-operate-8.5.6.zip

Once you download all of those, go to bin folder of each and replace the content of application.yml accordingly with the application files I have provided in the repo. 

Note: Replace the content not the file.

How to run it?
1. Run the elasticsearch from the config folder of elasticsearch.
2. Run the broker from the config folder of zeebe.
3. Run the operate from the config folder of operate.
4. Run the tasklist from the config folder of tasklist. -- You can run this only if you have some task in your application.
