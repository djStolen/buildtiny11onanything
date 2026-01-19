FROM mcr.microsoft.com/dotnet/sdk:9.0

RUN pwsh -c 'New-Item -Path $profile -ItemType File -Force' \
    && pwsh -c "'New-Alias \"tf\" \"terraform\"' | Out-File -FilePath \$profile"
