- 👋 Hi, I’m @vae-dong
- 👀 I’m interested in ...
- 🌱 I’m currently learning ..
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
vae-dong/vae-dong is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>综合案例</title>
</head>
<body>
    <h4>青春不常在，趁早谈念爱</h4>
    <table width="600">
        <!-- 第一行 -->
        <tr>
            <td>性别:</td>
            <td>
                <input type="radio" name="sex" id="nan"><label for="nan"><img src="images/man.jpg">男</label>
                <input type="radio" name="sex" id="nv"><label for="nv"><img src="images/women.jpg">女</label>
            </td>
        </tr>
       <!-- 第二行 -->
        <tr>
            <td>生日:</td>
            <td>
            <select>
                <option>--请选择年份--</option>
                <option>2000</option>
                <option>2001</option>
                <option>2002</option>
            </select>
            <select>
                <option>--请选择月份--</option>
                <option>01</option>
                <option>02</option>
                <option>03</option>
            </select>
            <select>
                <option>--请选择日期--</option>
                <option>01</option>
                <option>02</option>
                <option>03</option>
            </select>
            </td>
        </tr>   
        <!-- 第三行  -->
        <tr>
            <td>所在地:</td>
            <td>
                <input type="text" value="中国东京">
            </td>
        </tr>
        <!-- 第四行 -->
        <tr>
            <td>婚姻状况:</td>
            <td>
                <input type="radio" name="marry" checked="checked" id="weihun"><label for="weihun">未婚</label>
                <input type="radio" name="marry" id="liyi"><label for="liyi">离异</label>
                <input type="radio" name="marry" id="sangou"><label for="sangou">丧偶</label>
            </td>
        </tr>
        <!-- 第五行 -->
        <tr>
            <td>学历：</td>
            <td><input type="text" value="小学生"></td>
        </tr>
        <!-- 第六行 -->
        <tr>
            <td>喜欢的类型</td>
            <td>
                <input type="checkbox" name="love" id="fupo"><label for="fupo">富婆</label>
                <input type="checkbox" name="love" id="luoli"><label for="luoli">萝莉</label>
                <input type="checkbox" name="love" id="heisi"><label for="heisi">黑丝</label>
                <input type="checkbox" name="love" id="all" checked><label for="all">都喜欢</label>
            </td>
        </tr>
        <!-- 第七行 -->
        <tr>
            <td>个人简介：</td>
            <td>
                <textarea>个人简介</textarea>
            </td>
        </tr>
        <!-- 第八行 -->
        <tr>
            <td></td>
            <td>
                <input type="submit" value="免费注册">
            </td>
        </tr>
        <!-- 第九行 -->
        <tr>
            <td></td>
            <td>
                <input type="checkbox" name="agree" id="tongyi" checked><label for="tongyi" >我同意注册条款和会员加入标准</label>
            </td>
        </tr>
        <!-- 第十行 -->
        <tr>
            <td></td>
            <td>
                <a href="#">我是会员，立即登录</a>
            </td>
        </tr>
        <!-- 第十一行 -->
        <tr>
            <td></td>
            <td>
                <h5>我承诺</h5>
                <ul>
                    <li>年满18岁、单身</li>
                    <li>抱着严肃的态度</li>
                    <li>真诚寻找另一半</li>
                </ul>
            </td>
        </tr>
    </table>
</body>
</html>
