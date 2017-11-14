<template>
	<div class="resume">
		<div class="about">
			<h1 class="name">刘欣</h1>
			<div class="intention">职位：<span>web前端工程师</span></div>
			<div class="info">
			    <div class="info-title">资料：</div>
				<div class="info-item">
					<i class="icon school"></i>
					<span>竹云科技(成都分公司)</span>
				</div>
				<div class="info-item">
					<i class="icon major"></i>
					<span>成都</span>
				</div>
				<div class="info-item">
					<i class="icon phone"></i>
					<span>18382288321</span>
				</div>
				<div class="info-item">
					<i class="icon email"></i>
					<span>3358621@qq.com</span>
				</div>
			</div>
		</div>
		<div class="power">
			<div class="power-item">
                <div class="title">
                    <i class="icon technology"></i>
                    <span class="name">技术栈</span>
                </div>
                <div class="technology-item">
                    <span>【前端】</span>HTML/HTML5、CSS/CSS3、JavaScript(ES6,ES5)、SCSS、Gulp、Vue.JS、jQuery、模板引擎、混合开发、浏览器插件
                </div>
                <div class="technology-item">
                    <span>【后端】</span>Linux
                </div>
                <div class="technology-item">
                    <span>【数据库】</span>MySQL
                </div>
                <div class="technology-item">
                    <span>【自动化构建】</span>Webpack、Gulp
                </div>
                <div class="technology-item">
                    <span>【版本管理】</span>git、SVN
                </div>
            </div>
            <div class="power-item">
                <div class="title">
                    <i class="icon evaluation"></i>
                    <span class="name">个人评价</span>
                </div>
                <div class="myevaluation">开发过跨平台框架，乐于创建优秀的web界面，尤其是对界面的交互效果情有独钟，曾经担任过项目经理，对用户体验有很强烈的追求；轻度以上的代码洁癖；能独立承担跨平台APP和WEB的前端开发工作。会服务端，Linux，MySQL，能够基于linux服务器搭建Git版本控制系统。热爱前端，勤于学习，平均每天晚上3个小时的学习时间，经常活跃掘金，github，平时偶尔看看简书，欣赏生活。
                </div>
            </div>
		</div>
	</div>
</template>

<script>
	export default {

	}
</script>

<style lang="stylus" scoped>
.resume
    display: flex
    height: 100%
    .about
        width: 250px
        background-color: rgb(36,70,100)
        padding: 10px
        box-sizing: border-box
        color: #fff
        .name
            text-align: center
            margin: 20px auto 40px
            font-size: 28px
            font-weight: 600
        .intention
            font-size: 20px
            span
                display: block
                text-align: right
                font-size: 16px
                line-height: 18px
                margin: 20px 0
                letter-spacing: 1px
        .info
            .info-title
                font-size: 20px
            .info-item
                display: flex
                margin: 10px 0 20px 0
                height: 40px
                line-height: 40px
                .icon
                    width: 40px
                    height: 40px
                    background-color: #fff
                    border-radius: 50%
                    margin-right: 20px
                    background-position: center
                    background-repeat: no-repeat
                    background-size: 26px
                    &.school
                        background-image: url(school.png)
                    &.major
                        background-image: url(major.png)
                    &.phone
                        background-image: url(phone.png)
                        background-size: 32px
                    &.email
                        background-image: url(email.png)
    .power
        flex: 1
        overflow-y: auto
        padding: 30px
        background-color: #fff
        .power-item
            color: rgb(36,70,100)
            .title
                display: flex
                margin-bottom: 20px
                .icon
                    display: inline-block
                    width: 50px
                    height: 50px
                    background-color: rgb(36,70,100)
                    border-radius: 50%
                    margin-right: 10px
                    background-position: center
                    background-repeat: no-repeat
                    background-size: 30px
                    &.technology
                        background-size: 35px
                        background-image: url(technology.png)
                    &.evaluation
                        background-image: url(evaluation.png)
                .name
                    flex: 1
                    display: inline-block
                    height: 50px
                    font-size: 24px
                    font-weight: 600
                    line-height: 50px
                    box-sizing: border-box
                    border-bottom: 2px solid rgb(36,70,100)
            .technology-item
                margin: 20px auto
                font-size: 14px
                line-height: 25px
                display: flex
                span
                    display: inline-block
                    font-size: 18px
            .myevaluation
                text-indent: 2em
                line-height 1.5

</style>
