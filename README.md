# ���� [English](README_EN.md "English")
# IdentityServerDemo
����һ�� .net core �ۺ���ѧϰ��ʾ���ռ���Ŀ���������ֹ��ܵĻ���ʹ�ú��ۺ�Ӧ��ʾ����Ŀ���Ǿ����ܷ�����ٵ�չʾ���ֹ��ܵ�ʹ�÷�����ʵ��Ч����
<br> ��ǰ��ܰ汾�� .Net Core 3.1
<br> VS 2019 �汾�� 16.4.0 ����

## �����е�ʾ������
1. DemoApp
   1.  Client�� C# oidc �ͻ���ʾ������ʱ�Բ��Դ��롣
   2.  CSharpScriptDemo��ʹ�� Roslyn ���� C# �ű���ʾ����
   3.  DomianSample����ʱ�Բ��Դ��롣
   4.  GrpcClient������̨ gRPC �ͻ���ʾ����
   5.  IdentityServer����Ҫ��Ŀ�����пͻ��˵ķ���ˡ����������ʾ����
   6.  IdentityServerGui��IdentityServer �� ͼ�λ� ��ǡ�.net core 3.x Window ����Ӧ�ÿ���ʾ����WPF����
   7.  JavascriptClient��js oidc �ͻ���ʾ����
   8.  SudokuTset��������������Դ����ʹ��ʾ����
   9.  WebAPI mvc oidc �ͻ���ʾ����
   10. WebClient����ʱ����浵��
2. IdentityServerAdmin
   1.  IdentityServer.Admin��IdentityServer4 Web ������档���� IdentityServer��
   2.  IdentityServer.Admin.Api��IdentityServer4 Web Api������ IdentityServer��

## ʹ��˵��
### ���Է�ʽ
1. ������������Ŀ���� IdentityServerDemo ��������� <br>``` https://github.com/CoreDX9/IdentityServerDemo.git ```<br>``` https://github.com/CoreDX9/Harmonic.git ```
2. ж����Щ��Ŀ��<br>```Data/Domain.EntityFrameworkCore```<br>```Data/EntityHistoryMQReceive```<br>```Data/Repository```<br>```DemoApp/WebClient```<br>```Infrastructure/ResourceOwnerClient```
3. �޸� Infrastructure/Harmonic ����Ŀ���á�
4. �ȴ� VS2019 �Զ���ԭ Nuget �� npm ������� npm ���Զ���ԭʧ�ܣ��ɳ����� cmd ������ npm install �����ȷ���Ѱ�װ Node.js��
5. �� IdentityServer ����ΪĬ��������Ŀ������������ʽΪ���йܷ�ʽ��
6. �������ʵ������޸� IdentityServer/appsettings.json �� appsettings.Development.json �е����ݿ������ַ�����Ŀǰ��֧�� MS SqlServer����Ҫ�������ݿ�֧�ֵ��������޸Ĵ��롣
7. ���� IdentityServer ��Ŀ����ʼ���ò�̽������ʾ���ɡ�����ʾ����������ҳ�����ĵ������ҵ��������ҳ��ʾЧ���쳣���볢�Ե�����������ڴ�С�����ҳ�����ű�����
8. ���������Ȥ��������ִ�г�����Ŀ��

### ������ʽ
1. ����ǰ���˵��ȷ���������������ԡ�
2. �� IdentityServer ��Ŀ�ϵ����Ҽ���ѡ�񷢲���ѡ�� FolderProfileRelease �������ã�������Ŀ�����һ�������������ڽ�������ļ����ҵ� .publish �ļ��С�
3. �� IdentityServerGui ��Ŀ���ϵ����Ҽ���ѡ�񷢲���������Ŀ�����һ�������������� IdentityServer �ķ���λ���ҵ� IdentityServerGui.exe��
4. �������ʵ������޸� IdentityServer �� appsettings.json �� appsettings.Production.json �����ݿ������ַ�����
5. ˫�� IdentityServer.exe ���� IdentityServerGui.exe ���г���

### ע������
1. ����ʹ�ýϸ߰汾���������������Ҫʹ�� IE��
2. ��������޸� appsettings.json �ĸ����趨��
3. ʱ�侫�����ޣ��޷�ȫ����Գ��򣬿��ܻᷢ�����¿�ܻ���汾���¹����쳣����������з��֣���ӭ�� issue �������һᾡ���޸���
4. IdentityServer ��Ŀ����һ����ǩ���� CA ��֤�����վ֤�顣��ǩ��֤��Ĭ�ϻ��ڷ���ģʽ��ʹ�ã��䷢�� localhost ������ȷ���ڷ���ģʽ�¿�������ʹ�� Https Э�顣
5. ʹ�����ṩ�����÷�����Ŀ�������ȫ�°�װ�� Windows 7 Sp1 �����߰汾��ϵͳ��ֱ�����У�û���κ�������ǰ����������������Ϊʹ���ڴ����ݿ⣬�����������ʾ����
6. ���ݿ�Ĭ�ϻ��ض��� IdentityServer ��Ŀ�� App_Data/Database �ļ��С�ͬʱΪ�����õ���ģʽ�ͷ���ģʽ�ĳ������л������ţ����ݿ�����Ĭ�ϰ������л�����׺��
---
## ������ʾ��
### IdentityServer
1. �Զ�����Ŀ�������ã�ͨ���޸� csproj ��Ŀ�ļ�ʵ��ȫ�Զ���������
2. JQuery��Bootstrap4��Lay UI��Vue��Element-UI��Avue��Axios��Monaco-editor ���ڶೣ��ǰ�˿�ܺͿ��ʹ�á�
3. IdentityServer4 �� Identity Core ��ʹ�ã�SSO ����֧�֡�
4. Identity Core ����IdentityServer4 ����
5. Identity Core ��˽���ݱ�����
6. Identity Core ˫������֤��������¼�������ֻ������ Microsoft Authenticator �� Google Authenticator Ӧ��ʹ�á�
7. gRPC ����ı�д��ʹ�ã���� GrpcClient��
8. Web ȫ��֧�֣���ҳ���ػ��������
9. ������ַ���ȫ���뱾�ػ�֧�֡�ͬʱʹ�û��� resx ��Դ�ͻ������ݿ���ַ������ػ����ܡ�����ʹ�� resx ��Դ������ʧ�ܺ�ʹ�����ݿ����ݡ�
10. ������ EF Core Ǩ�Ƴ�����ȫ�Զ�Ǩ�ƺ����ݳ�ʼ�����ο���[����Ǩ��](src/DemoApp/IdentityServer/EFCoreMigrationReadme.md "����Ǩ��")��
11. EF Core ȫ�Զ���ɾ����ѯ���ˡ�
12. �� asp.net core Web Ӧ�ð�װΪ Windows ����Ӧ�á�
13. ʹ�� Roslyn ���� C# �ű������� Try.Net ���֣���ʹ�� ILSpy ������ .net ���͡�ʹ�� monaco editor չʾ�ͱ༭���롣
14. ��汾 Web Open Api ֧�֣�IdentityServer4 OAuth 2.0 ���ɡ�
15. Swagger ��汾 Api ����͵��ԣ�OAuth 2.0 ֧�֡�
16. Mvc �ս���б������
17. DI ��ע��ķ����б������
18. �ļ������
19. Ӧ�ý�����顣
20. ����ֱ�����񡣣�����ȱ�ݣ���֧�� FFmpeg �����е��ã�
21. Razor Page ʹ��ʾ����
22. FluentValidation��Razor Page�������Լ����ۺ�ʾ����
23. SignalR ʵʱ����ʾ��������SignalR��Web ������������ʾ�������ɷ��� Hub ʾ����
24. ���򼯶�̬���롢���á�ж��ʾ����.net core 3.0 �������ܣ���
25. �����������ҳ����ʾ�������� Vue �����ݰ󶨡�
26. �޽��������ʹ��ʾ�������� Puppeteer��Chromium79.
27. video.js ʹ�ú���չʾ�������� CCL ��Ļ���棬���� flv.js ʵ�� HTML5 ֱ��֧�� flv ��ʽ��Ƶ�Ĳ��š�
28. ����������Ĺ�ѧ�ַ�ʶ��ʹ��ʾ����
29. �����ݵ����ݿ�˵����չ��
30. Razor ��ͼ��ȾΪ�ַ�������ʾ����
31. MiniProfiler ʾ����
#### ���и��࡭��

### IdentityServerGui
1. .net core DI �� WPF ���ɡ�
2. PropertyChanged.Fody ���ɡ�
3. ֪ͨ��֧�֡�
#### ���и��࡭��