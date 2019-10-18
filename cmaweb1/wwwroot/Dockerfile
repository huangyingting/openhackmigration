# escape=`
FROM mcr.microsoft.com/dotnet/framework/aspnet:4.7.2

COPY . /inetpub/wwwroot

#RUN powershell remove-website -name 'Default Web Site'
#RUN powershell New-Website -Name 'Default Web Site' -Port '2901' -PhysicalPath 'c:\inetpub\wwwroot'

EXPOSE 80