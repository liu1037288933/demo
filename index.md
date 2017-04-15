<!DOCTYPE html>
<html>

	<head>
		<meta charset="UTF-8">
		<title></title>
		<style type="text/css">
		    .content {
		    	
		    }
		
		
            /*搜索栏*/
			
			.input-row-h {
				display: inline-block;
				margin-right: 8px;
			}
			
			.input-row-h input {
				width: 114px;
				height: 10px;
				font-size: 14px;
			}
			.search-box {
				margin-bottom: 10px;
			}
			.box-body select {
				width: 132px;
			    height: 30px;
			    font-size: 14px;
			    padding: 0;
			    
			}
			select {
				color: #666;
				
			}
			
			
			.search {
				width: 84px;
			    height: 32px;
			    font-size: 14px;
			    line-height: 32px;
			    padding: 0;
			}
			.box-body .label-h {
				float: left;
				height: 30px;
                line-height: 30px;
			}
			.box-body .input-h {
				float: right;
			}
			
			/*表格样式*/
			.box-body .ID {
				width: 200px;
			}
			.box-body .address {
				width: 706px;
			}
			
			
			/*个人简历样式*/
			.td-person {
				width: 80px;
			}
			.p-row {
				border: none;
			}
			
			.td-danwei {
				padding: 7px 0;
			}
			.box2 input {
				outline: none;
			}
			
		</style>

	</head>

	<body>
		<div id="wrapper">
			<div class="main" id="blue">
				<!--顶部导航栏-->
				<div class="nav">
					<div class="nav-main">
						<div class="nav-logo">
							<a href="index.html">培训学校</a>
						</div>
						<div class="nav-actions">
							<div class="nav-user">
								<div class="nav-item nav-item-active">
									<div class="nav-tick">
										<div class="nav-item-cog">管理</div>
									</div>
								</div>
								<div class="nav-item">

									<div class="nav-tick">
										admin [
										<a href="http://liuzhjx.aspark.cn/login/logout">退出</a>]
									</div>
								</div>
							</div>
							<div class="nav-list">
                <div class="nav-item">
                	<a href="">
                		<div class="nav-tick">
                			<div class="nav-item-news">新闻公告</div>

                		</div>
                	</a>
                </div>
                
                <div class="nav-item">
                	<a href="">
                		<div class="nav-tick">
                			<div class="nav-item-departments">部门机构</div>
                		</div>
                	</a>
                </div>
                
                <div class="nav-item">
                	<a href="">
                		<div class="nav-tick">
                			<div class="nav-item-events">校园活动</div>
                		</div>
                	</a>
                </div>
                
                <div class="nav-item">
                	<a href="">
                		<div class="nav-tick">
                			<div class="nav-item-files">共享文件</div>
                		</div>
                	</a>
                </div>
                
							</div>
						</div>
					</div>
				</div>
				<!--/顶部导航栏-->

				<div class="page">
					<!--左侧菜单栏-->
					<div class="side">
						<div class="side-main">
							<div class="side-list">
								<div class="side-title">
									个人信息
								</div>
								<a href="Myclass.html">
									<div class="side-item">
										<div class="side-tick">
											<div class="xx">我的课程</div>
										</div>
									</div>

								</a>
								<a href="jingtitest.html">
									<div class="side-item">
										<div class="side-tick">
											<div class="xx">警体测试</div>
										</div>
									</div>

								</a>
								<a href="mygrades.html">
									<div class="side-item">
										<div class="side-tick">
											<div class="xx">我的成绩</div>
										</div>
									</div>

								</a>
								<a href="Notice.html">
									<div class="side-item">
										<div class="side-tick">
											<div class="xx">通知公告</div>
										</div>
									</div>

								</a>
								<a href="Password.html">
									<div class="side-item">
										<div class="side-tick">
											<div class="xx">账号密码</div>
										</div>
									</div>

								</a>
							</div>
						</div>
						<div class="side-footer">
							<div class="side-footer-text">
								@Hi
							</div>
						</div>
					</div>
					<!--/左侧菜单栏-->
					<!--右侧内容区-->
					<div class="content">
						<div class="span12">
							<div class="box">
								<div class="box-header search-box">
									<div class="box-title text-center">
										个人信息
									</div>
									
								</div>
								<div class="box-body">
									<form action="" method="">
										<div class="input-row-h">
											<div class="label-h">姓名：</div>
											<div class="input-h">
												<input type="text" name="name" value="" placeholder="请输入姓名">
											</div>
										</div>
										<div class="input-row-h">
											<div class="label-h">性别：</div>
											<div class="input-h">
												<select name="sec">
													<option selected="selected" value="">请选择性别</option>
													<option value="1">男性</option>
													<option value="2">女性</option>
												</select>
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">出生年月：</div>
											<div class="input-h">
												<input type="text" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											</div>
										</div>
										<div class="input-row-h" style="float: right;">
									
											<div class="input-h">
												<img style="width: 100px;height: 100px; background-color: lightblue;" alt="" />
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">学号：</div>
											<div class="input-h">
												<input type="text" name="name" value="" placeholder="请输入学号">
											</div>
										</div>
										
										<div class="input-row-h">
											<div class="label-h">民族：</div>
											<div class="input-h">
												<select name="sec">
													<option selected="selected" value="">请选择民族</option>
													<option value="1">汉族</option>
													<option value="2">苗族</option>
												</select>
											</div>
										</div>
										
										<div class="input-row-h">
											<div class="label-h">文化程度：</div>
											<div class="input-h">
												<select name="sec">
													<option selected="selected" value="">请选择文化程度</option>
													<option value="1">研究生</option>
													<option value="2">本科</option>
												</select>
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">身份证号：</div>
											<div class="input-h">
												<input class="ID" type="text" name="name" value="" placeholder="请输入身份证号">
											</div>
										</div>
										<div class="input-row-h">
											<div class="label-h">政治面貌：</div>
											<div class="input-h">
												<select name="sec">
													<option selected="selected" value="">请选择政治面貌</option>
													<option value="1">团员</option>
													<option value="2">党员</option>
												</select>
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">入党时间：</div>
											<div class="input-h">
												<input type="text" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">入学时间：</div>
											<div class="input-h">
												<input type="text" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											</div>
										</div>
										<div class="input-row-h">
											<div class="label-h">婚否：</div>
											<div class="input-h">
												<select name="sec">
													<option selected="selected" value="">请选择</option>
													<option value="1">未婚</option>
													<option value="2">已婚</option>
												</select>
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">邮编：</div>
											<div class="input-h">
												<input type="text" name="name" value="" placeholder="请输入邮政编码">
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">家庭住址：</div>
											<div class="input-h">
												<input class="address" type="text" name="name" value="" placeholder="请输入身份证号">
											</div>
										</div>
										<div class="input-row-h">
										    <div class="label-h">工作单位：</div>
											<div class="input-h">
												<input class="ID" type="text" name="name" value="" placeholder="请输入身份证号">
											</div>
										</div>
										<div class="input-row-h">
											<div class="label-h">职务：</div>
											<div class="input-h">
												<input type="text" name="name" value="" placeholder="请输入姓名">
											</div>
										</div>
										<div class="input-row-h">
											<div class="label-h">联系电话：</div>
											<div class="input-h">
												<input type="text" name="name" value="" placeholder="请输入姓名">
											</div>
										</div>
										
									</form>
								</div>
							</div>
							<div class="box box2">
								<div class="box-header search-box">
									<div class="box-title text-center">
										个人简历
									</div>
									
								</div>
								<div class="box-body">
									<form action="" method="">
										<table border="0" cellspacing="0" cellpadding="0">
											<tr>
												<th></th>
												<th>开始时间</th>
												<th>结束时间</th>
												<th>学校及单位名称</th>
												<th>证明人</th>
											</tr>
											<tr class="table-row">
												<td class="td-main">1</td>
												<td class="text-center td-person">
												    <div class="input-row-h person-table">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center td-person">
												    <div class="input-row-h">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入学校及单位名称">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 113px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入证明人姓名">
											
										            </div>
												</td>
											</tr>
											<tr class="table-row">
												<td class="td-main">2</td>
												<td class="text-center td-person">
												    <div class="input-row-h person-table">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center td-person">
												    <div class="input-row-h">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入学校及单位名称">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 113px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入证明人姓名">
											
										            </div>
												</td>
											</tr>
											<tr class="table-row">
												<td class="td-main">3</td>
												<td class="text-center td-person">
												    <div class="input-row-h person-table">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center td-person">
												    <div class="input-row-h">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入学校及单位名称">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 113px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入证明人姓名">
											
										            </div>
												</td>
											</tr>
											<tr class="table-row">
												<td class="td-main">4</td>
												<td class="text-center td-person">
												    <div class="input-row-h person-table">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center td-person">
												    <div class="input-row-h">
										  
												       <input type="text" class="p-row" id="selectDate" readonly="readonly" placeholder="请选择日期"/>
											           
									                </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入学校及单位名称">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 113px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;" type="text" name="name" value="" placeholder="请输入证明人姓名">
											
										            </div>
												</td>
											</tr>
											
									    </table>
										
									</form>
								</div>
							</div>
							
							<div class="box">
								<div class="box-header search-box">
									<div class="box-title text-center">
										家庭成员和主要社会关系
									</div>
									
								</div>
								<div class="box-body">
									<form action="" method="">
										<table border="0" cellspacing="0" cellpadding="0">
											<tr>
												<th></th>
												<th>关系</th>
												<th>姓名</th>
												<th>年龄</th>
												<th>工作单位</th>
											</tr>
											<tr class="table-row">
												<td class="td-main">1</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入关系">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入姓名">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入年龄">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 371px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入工作单位">
											
										            </div>
												</td>
											</tr>
											<tr class="table-row">
												<td class="td-main">2</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入关系">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入姓名">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入年龄">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 371px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入工作单位">
											
										            </div>
												</td>
											</tr>
											<tr class="table-row">
												<td class="td-main">3</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入关系">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入姓名">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入年龄">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 371px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入工作单位">
											
										            </div>
												</td>
											</tr>
											<tr class="table-row">
												<td class="td-main">4</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入关系">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入姓名">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入年龄">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 371px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入工作单位">
											
										            </div>
												</td>
											</tr>
											<tr class="table-row">
												<td class="td-main">5</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入关系">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入姓名">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;">
													<div class="input-row-h" style="width: 100%;">
											 
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入年龄">
											
										            </div>
												</td>
												<td class="text-center" style="padding: 9px 0;width: 371px;">
												    <div class="input-row-h" style="width: 100%;">
											   
												        <input style="border: none;width: 100%;margin-right: 0;padding: 9px 0;outline: none;" type="text" name="name" value="" placeholder="请输入工作单位">
											
										            </div>
												</td>
											</tr>
											
											
									    </table>
										<button style="float: right;" type="submit" class="btn btn-submit search" name="search" value="search">编辑</button>
									</form>
								</div>
							</div>
						</div>
					</div>
					
				</div>

			</div>

		</div>
<script type="text/javascript">
	
</script>
	</body>

</html>
