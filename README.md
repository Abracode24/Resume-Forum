# Resume-Form
Resume forum in HTML. Beginner's first steps
<!DOCTYPE html>
<html lang="az-AZ">
    <head>
        <meta charset="UTF-8">
        <title>Test</title>
    </head>
    <body>
        <h1 style="text-align:center;"><strong><em><mark><ins>Elektron Resume</ins></mark></em></strong></h1>
        <!--Form kodlarını div içine CSS için yazdım-->
        <div>
            <form>
                <fieldset>
                    <legend>Form</legend>
                    <table>
                        <tr>
                            <td><span>Adınız:</span></td>
                            <td><input type="text"></td>
                        </tr>
                        <tr>
                            <td><span>Soyadınız:</span></td>
                            <td><input type="text"></td>
                        </tr>
                        <tr>
                            <td><span>Email:</span></td>
                            <td><input type="email" required></td>
                        </tr>
                        <tr>
                            <td><label for="prl"><span>Parol:</span></label></td>
                            <td><input type="password" id="prl" name="prl" maxlength="6"></td>
                        </tr>
                        <tr>
                            <td><span>Sahə:</span></td>
                            <td><label for="frontend">Frontend</label><input type="radio" id="frontend" name="jdeveloper" value="JuniorFrontend"><label for="backend">Backend</label><input type="radio" id="backend" name="jdeveloper" value="JuniorBackend"></td>
                        </tr>
                        <tr>
                            <td><label for="level">Səviyyə:</label></td>
                            <td><select id="level" name ="skill">
                                   <option value="Junior">Junior</option>
                                   <option value="Middle">Middle</option>
                                   <option value="Senior">Senior</option></select></td>
                        </tr>
                        <tr>
                            <td colspan="2"><textarea id="about" rows="5" cols="40" placeholder="Haqqınızda..."></textarea></td>
                        </tr>
                        <tr>
                            <td><label for="myfile">CV yüklə:</label></td>
                            <td><input type="file" id="myfile" name="cvfile"></td>
                        </tr>
                        <tr>
                            <td colspan="2" style="text-align:center;"><span>Tool skills:</span></td>
                        </tr>
                        <tr>
                            <td colspan="2"><input type="checkbox" id="html" name="html" value="dil1"><label for="html">HTML</label><br><input type="checkbox" id="css" name="css" value="dil2"><label for="css">CSS</label><br><input type="checkbox" id="javascript" name="javascript" value="dil3"><label for="javascript">Javascript</label><br><input type="checkbox" id="react" name="react" value="dil4"><label for="react">React</label></td>
                        </tr>
                        <tr>
                            <td colspan="2"><input type="submit" value="Göndər"></td>
                        </tr>
                    </table>
                </fieldset>
            </form>
        </div>
    </body>
</html>
