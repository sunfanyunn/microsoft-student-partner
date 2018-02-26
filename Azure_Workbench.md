# Machine learning workbench


Azure machine learning是一個可讓您管理整個資料科學生命週期的機器學習解決方案。 
包含以下幾個核心元件：
* Azure Machine Learning Workbench
* Azure Machine Learning 測試服務
* Azure Machine Learning 模型管理服務

如果資料科學生命週的角度來看的話可以改略的分成三大步驟：

* 資料前處理(Data preparation)
* 模型開發和測試(Experimentation)
* 各種目標環境中的模型部署(Deployment)

可以參照這張圖來了解上續的幾個核心元件在資料科學生命週期裡扮演的角色。

![Taken from microsoft docs](https://docs.microsoft.com/zh-tw/azure/machine-learning/preview/media/overview-what-is-azure-ml/aml-concepts.png)

基本上測試服務對應到模型開發和測試，而模型管理服務對應到各種目標環境中的模型部署。Azure Machine Learning Workbench則是一個桌面應用程式。
以下是 Azure Machine Learning Workbench 所提供的核心功能：

* By-Example Data Transform

	容易上手且對於熟悉excel的人尤是。簡而言之就是對data的幾個example做你想要的transformation，電腦會從你的sample中學習這是什麼樣的transform並apply到所有的data上。自己寫script可能要寫regex的事情使用By-Example Data Transform的功能可以省去這個步驟節省data preprocessing的時間。

* 資料來源抽象可透過 UX 和 Python 程式碼存取。

* Command Line Interface
	
* Python SDK 用於叫用以視覺化方式建構的資料準備封裝。

* 內建 Jupyter Notebook 服務。
		
    詳細請參考:[https://docs.microsoft.com/zh-tw/azure/machine-learning/preview/how-to-use-jupyter-notebooks]()

* 透過執行歷程記錄檢視測試監視及管理。

* 角色型存取控制，允許透過 Azure Active Directory 的共用及協同作業。
* 由原生的 Git 整合所啟用的每個執行的自動專案快照集，以及明確的版本控制。
* 與受歡迎 Python IDE 的整合。
	
    目前可以支援visual studio code跟pycharm。



上手的步驟如下:
1. Create an Azure machine learning experimentation account
2. Install machine learning workbench on one of the following OS:
	* Windows 10
	* Windows Server 2016
	* macOS Sierra
	* macOS High Sierra
3. Create a new project!

更詳細的步驟可以參考: [https://docs.microsoft.com/zh-tw/azure/machine-learning/preview/quickstart-installation]().


心得: 
對我而言比較嚴重的缺點就是支援的


reference:

* [https://docs.microsoft.com/zh-tw/azure/machine-learning/preview/overview-what-is-azure-ml#azure-machine-learning-model-management-service]()
* microsoft official documentation


