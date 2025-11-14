과제1.
train_image[6000] 이미지 모습을 출력해서, 화면 캡쳐 후 코드와 함께 github 에 올릴 것. 
作业 1. 打印出 train_image[6000] 图像，截屏，并将其与代码一起上传到 GitHub。


<img width="353" height="374" alt="task1" src="https://github.com/user-attachments/assets/1ada1824-c76e-46dd-85c5-f37cbfe458ab" />


과제2.
train_image[1000]
train_image[2000]
train_image[3000]
train_image[4000]
이미지를 
ax1
ax2
ax3
ax4
에 보이게 하고, 화면 캡쳐 후 코드와 함께 github 에 올릴 것. 

作业 2.
train_image[1000]
train_image[2000]
train_image[3000]
train_image[4000]

显示以下图像：
ax1
ax2
ax3
ax4

，截取屏幕截图，并将其与代码一起上传到 GitHub。


<img width="692" height="188" alt="task2" src="https://github.com/user-attachments/assets/8198dd14-7dbd-4da7-ac60-96c9aff7ae4d" />

과제3.
model 만들 때, hidden layer의 노드 갯수 256을 128로 한 뒤,
model.summary() 실행 모습을 화면 캡쳐 후 코드와 함께 github 에 올릴 것. 

作业 3. 创建模型时，将隐藏层中的节点数从 256 更改为 128。然后，截取 model.summary() 执行的屏幕截图，并将其与代码一起上传到 GitHub。

<img width="600" height="224" alt="task3" src="https://github.com/user-attachments/assets/591c4f1e-77b5-4f0b-93d5-5173b46ba489" />


과제4.
최적화 함수로 adam 대신 sgd 함수를 사용하여 compile 한 모습을 화면 캡쳐 후 코드와 함께 github 에 올릴 것. 

作业 4. 使用 sgd 函数而不是 adam 优化函数编译程序后，截取屏幕截图，并将其与代码一起上传到 GitHub。

<img width="831" height="226" alt="task4" src="https://github.com/user-attachments/assets/febb9784-baf7-40c2-bc22-605cae281937" />


과제5.
성능 측정을 metrics=['accuracy'] 로 하였는데, 
epochs=2 일때의 accuracy의 값과 
epochs=5 일때의 accuracy의 값을 비교해서 왜 다른지를 설명하는 것을 github 에 올릴 것. 

任务 5. 使用 metrics=['accuracy'] 来衡量性能。比较 epochs=2 和 epochs=5 时的准确率值，并解释它们差异的原因。将文件上传到 GitHub。과제5.
성능 측정을 metrics=['accuracy'] 로 하였는데, 
epochs=2 일때의 accuracy의 값과 
epochs=5 일때의 accuracy의 값을 비교해서 왜 다른지를 설명하는 것을 github 에 올릴 것. 

任务 5. 使用 metrics=['accuracy'] 来衡量性能。比较 epochs=2 和 epochs=5 时的准确率值，并解释它们差异的原因。将文件上传到 GitHub。

<img width="677" height="775" alt="task5" src="https://github.com/user-attachments/assets/a21c297f-11e9-4c20-ae73-1042cf4b0c0c" />



解释（Explanation）

epochs=2：权重尚未充分学习 → 准确率较低

epochs=5：对数据更多次迭代学习 → 损失减少、准确率提高

epoch 越高越容易学习充分，但过多可能导致过拟合

