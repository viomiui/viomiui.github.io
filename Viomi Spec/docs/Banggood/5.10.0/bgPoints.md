
!!! Note
	低保真 UI Flow 在蓝湖，[点击查看](https://lanhuapp.com/web/#/item/board?pid=ddb8f764-f978-4035-896b-95081612e0d4)
	
	邀请码：[点我](https://lanhuapp.com/url/PYMpv)。有效期至 `2018-04-22`


### 1. 订单 - 未选择
![][image-1]

1. 显示 `可使用的 BG Points` 以及 `减免的金额`，点击可勾选，见 [2-1. 订单 - 选择使用 BG Points][1]
2. 显示用户账号下 `拥有的优惠券的总数`，点击进入 [3-1. 优惠券][2]


### 1-1. 订单 - 未选择  - 用户未登录

!!! Attention
	此状况仅适用于用户未登录状态

![][image-2]

1. 点击输入框进行输入优惠券代码
2. 点击 **Use** 按钮对优惠券向服务器提交本次订单使用的优惠券代码
	- 若 `未输入` 优惠券代码，点击 **Use** 按钮时没有反应
	- 若输入 `无效` 的优惠券代码，点击 **Use** 按钮后弹出对应的错误提示与现行版本一致
	- 若输入 `有效` 的优惠券代码，点击 **Use** 按钮后进入 [1-2. 订单 - 选择使用优惠券  - 用户未登录][3]


### 1-2. 订单 - 选择使用优惠券  - 用户未登录

!!! Attention
	此状况仅适用于用户未登录状态

![][image-3]

1. 显示使用 `优惠券成功` 和本次订单 `减免的金额`
2. 点击 **Clear** 按钮将删除优惠券，即本次订单不使用优惠券，返回至 [1-1. 订单 - 未选择  - 用户未登录][4]
3. Order Total 中加入 `Coupon discount` 一项的明细


### 2-1. 订单 - 选择使用 BG Points
![][image-4]

1. 已勾选使用 BG Points
2. 显示用户账号下 `拥有的优惠券的总数`，点击进入 [3-1. 优惠券][5]，并反选 **Using `45` Points** 一项
3. 当选中使用 BG Points 时，出现 **Edit** 按钮，可对使用多少 BG Points 进行编辑。点击 **Edit** 按钮进入 [2-2. 订单 - 选择使用 BG Points - 编辑][6]
4. Order Total 中加入 `BG Points discount` 一项的明细
5. 点击 **Clear** 按钮会取消选择使用 BG Points 的优惠，返回至 [1. 订单 - 未选择][7]


### 2-2. 订单 - 选择使用 BG Points - 编辑
![][image-5]

1. 光标默认 Focus 在输入框中，默认填入最大可用的 BG Points。点击右侧的 **Clear Button** 可清空输入框的内容，见 [2-3. 订单 - 选择使用 BG Points - 编辑 - 清空输入框][8]
2. 点击 **Redeem** 按钮向服务器提交本次订单使用的 BG Points
	- 若输入 `小于或等于` 可用 BG Points 的数字，返回至 [2-1. 订单 - 选择使用 BG Points][9]
	- 若输入`大于` 可用 BG Points 的数字，弹出错误提示，见 [2-5. 订单 - 选择使用 BG Points - 编辑 - 无效输入][10]
	- 输入 `0` 的错误提示与现行版本一致
3. 显示用户本次订单可用的 BG Points
4. 点击 **关闭** 按钮或 Overlay 区域关闭本次输入，且不对已修改的数字进行保存，返回至 [2-1. 订单 - 选择使用 BG Points][11]


### 2-3. 订单 - 选择使用 BG Points - 编辑 - 清空输入框
![][image-6]

1. Placeholder 显示用户最大可用的 BG Points 数值，显示格式为 MAX: `45`
2. 由于输入框没有任何已输入的数字，点击 **Redeem** 按钮没有反应
3. 显示用户本次订单可用的 BG Points
4. 点击 **关闭** 按钮或 Overlay 区域关闭本次输入，且不对已修改的数字进行保存，返回至 [2-1. 订单 - 选择使用 BG Points][12]


### 2-4. 订单 - 选择使用 BG Points - 编辑 - 输入其他数字
![][image-7]

1. 输入其他数字。点击右侧的 **Clear Button** 可清空输入框的内容，见 [2-3. 订单 - 选择使用 BG Points - 编辑 - 清空输入框][13]
2. 点击 **Redeem** 按钮向服务器提交本次订单使用的 BG Points
	- 若输入 `小于或等于` 可用 BG Points 的数字，返回至 [2-1. 订单 - 选择使用 BG Points][14]
	- 若输入`大于` 可用 BG Points 的数字，弹出错误提示，见 [2-5. 订单 - 选择使用 BG Points - 编辑 - 无效输入][15]
	- 输入 `0` 的错误提示与现行版本一致
3. 显示用户本次订单可用的 BG Points
4. 点击 **关闭** 按钮或 Overlay 区域关闭本次输入，且不对已修改的数字进行保存，返回至 [2-1. 订单 - 选择使用 BG Points][16]


### 2-5. 订单 - 选择使用 BG Points - 编辑 - 无效输入
![][image-8]

1. 显示本次订单最大可用的 BG Points 数值
2. 点击 **OK** 按钮关闭 Alert，返回至 [2-4. 订单 - 选择使用 BG Points - 编辑 - 输入其他数字][17]


### 3-1. 优惠券
![][image-9]

1. 点击 **返回** 按钮返回至 [1. 订单 - 未选择][18]
2. 点击输入框进行输入优惠券代码，见 [3-2. 优惠券 - 输入代码][19]
3. 显示可用优惠券的信息，点击整个优惠券可勾选右侧 Checkbox，见 [3-3. 优惠券 - 选择优惠券][20]
4. 显示不可用的优惠券
5. 预览优惠券不可用的原因，点击右侧的 **展开** 按钮展开不可用原因，见 [3-1-1. 优惠券 - 不可用优惠券展开状态][21]


### 3-1-1. 优惠券 - 不可用优惠券展开状态
![][image-10]

1. 点击 **返回** 按钮返回至 [1. 订单 - 未选择][22]
2. 点击 **收起** 按钮收起优惠券不可用原因，见 [3-1. 优惠券][23]

### 3-2. 优惠券 - 输入代码
![][image-11]

1. 点击 **返回** 按钮返回至 [1. 订单 - 未选择][24]
2. 进行输入优惠券代码，点击右侧的 **Clear Button** 可清空输入框的内容，见 [3-1. 优惠券][25]
	- iOS 版本点击键盘中的 **Done** 按钮也可向服务器提交本次订单使用的优惠券代码
3. 点击 **Use** 按钮对优惠券向服务器提交本次订单使用的优惠券代码
	- 若 `未输入` 优惠券代码，点击 **Use** 按钮时没有反应
	- 若输入 `无效` 的优惠券代码，点击 **Use** 按钮后弹出对应的错误提示与现行版本一致
	- 若输入 `有效` 的优惠券代码，点击 **Use** 按钮后返回至 [3-7. 订单 - 选择使用优惠券][26]
4. 显示可用优惠券的信息，点击整个优惠券可勾选右侧 Checkbox，见 [3-3. 优惠券 - 选择优惠券][27]


### 3-3. 优惠券 - 选择优惠券
![][image-12]

1. Loading 中，成功后返回至 [3-7. 订单 - 选择使用优惠券][28]
2. 自动将选中的优惠券中的 `code` 写入输入框中


### 3-3-1. 优惠券 - 已选择优惠券
![][image-13]

1. 点击 **返回** 按钮返回至 [3-7. 订单 - 选择使用优惠券][29]
2. 显示已勾选的可用优惠券，可以进行反选，反选后见 [3-1. 优惠券][30]


### 3-4. 优惠券 - 无可用优惠券
![][image-14]

1. 点击 **返回** 按钮返回至 [1. 订单 - 未选择][31]
2. 点击输入框进行输入优惠券代码，见 [3-2. 优惠券 - 输入代码][32]
3. 提示用户无可用优惠券的信息


### 3-5. 优惠券 - 无不可用优惠券
![][image-15]

1. 点击 **返回** 按钮返回至 [1. 订单 - 未选择][33]
2. 点击输入框进行输入优惠券代码，见 [3-2. 优惠券 - 输入代码][34]
3. 显示可用优惠券的信息，点击整个优惠券可勾选右侧 Checkbox，见 [3-3. 优惠券 - 选择优惠券][35]
4. 提示用户无不可用优惠券的信息


### 3-6. 优惠券 - 无优惠券
![][image-16]

1. 点击 **返回** 按钮返回至 [1. 订单 - 未选择][36]
2. 点击输入框进行输入优惠券代码，见 [3-2. 优惠券 - 输入代码][37]
3. 提示用户没有任何优惠券的信息


### 3-7. 订单 - 选择使用优惠券
![][image-17]

1. 显示 `使用优惠券成功` 和本次订单 `减免的金额`
	- 点击 **Edit** 按钮进入查看使用优惠券的详情，见 [3-3-1. 优惠券 - 已选择优惠券][38]
2. 显示 `可使用的 BG Points` 以及 `减免的金额`，点击可勾选，见 [2-1. 订单 - 选择使用 BG Points][39]，并反选 **Coupon Successfully Used** 一项
3. Order Total 中加入 `Coupon discount` 一项的明细
4. 点击 **Clear** 按钮将删除优惠券，即本次订单不使用优惠券，返回至 [1. 订单 - 未选择][40]

[1]:	#2-1-bg-points
[2]:	#3-1
[3]:	#1-2-
[4]:	#1-1-
[5]:	#3-1
[6]:	#2-2-bg-points-
[7]:	#1-
[8]:	#2-3-bg-points-
[9]:	#2-1-bg-points
[10]:	#2-5-bg-points-
[11]:	#2-1-bg-points
[12]:	#2-1-bg-points
[13]:	#2-3-bg-points-
[14]:	#2-1-bg-points
[15]:	#2-5-bg-points-
[16]:	#2-1-bg-points
[17]:	#2-4-bg-points-
[18]:	#1-
[19]:	#3-2-
[20]:	#3-3-
[21]:	#3-1-1-
[22]:	#1-
[23]:	#3-1
[24]:	#1-
[25]:	#3-1
[26]:	#3-7-
[27]:	#3-3-
[28]:	#3-7-
[29]:	#3-7-
[30]:	#3-1
[31]:	#1-
[32]:	#3-2-
[33]:	#1-
[34]:	#3-2-
[35]:	#3-3-
[36]:	#1-
[37]:	#3-2-
[38]:	#3-3-1-
[39]:	#2-1-bg-points
[40]:	#1-

[image-1]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/1.%20Place%20Order%20-%20None%20Selected.png
[image-2]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/1-1.%20Place%20Order%20-%20None%20Selected%20-%20Sign%20Out.png
[image-3]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/1-2.%20Place%20Order%20-%20Coupon%20Selected%20-%20Sign%20Out.png
[image-4]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/2-1.%20Place%20Order%20-%20Select%20Points.png
[image-5]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/2-2.%20Place%20Order%20-%20Select%20Points%20-%20Edit%20Points.png
[image-6]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/2-3.%20Place%20Order%20-%20Select%20Points%20-%20Edit%20Points%20-%20Clear%20Text%20Field.png
[image-7]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/2-4.%20Place%20Order%20-%20Select%20Points%20-%20Edit%20Points%20-%20Other%20Number.png
[image-8]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/2-5.%20Place%20Order%20-%20Select%20Points%20-%20Edit%20Points%20-%20Invalid%20Input.png
[image-9]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-1.%20Place%20Order%20-%20Coupons.png
[image-10]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-1-1.%20Place%20Order%20-%20Coupons%20-%20Expand%20Unavailable%20Coupon.png
[image-11]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-2.%20Place%20Order%20-%20Select%20Coupon%20-%20Enter%20code.png
[image-12]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-3.%20Place%20Order%20-%20Select%20Coupon.png
[image-13]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-3-1.%20Place%20Order%20-%20Selected%20Coupon.png
[image-14]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-4.%20Place%20Order%20-%20No%20Available%20Coupons.png
[image-15]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-5.%20Place%20Order%20-%20No%20Unavailable%20Coupons.png
[image-16]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-6.%20Place%20Order%20-%20No%20Coupons.png
[image-17]:	http://image-lumpy.oss-cn-hangzhou.aliyuncs.com/Banggood_Spec/5.8.2/bgPoints/3-7.%20Place%20Order%20-%20Coupon%20Selected.png