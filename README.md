<ContentPage xmlns="http://schemas.microsoft.com/dotnet/2021/maui"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             x:Class="Mentac1.MainPage">

    <VerticalStackLayout Spacing="20" HorizontalOptions="Center" VerticalOptions="Center">

        <Label Text="EXPECTATION VS REALITY"
               FontSize="24"
               FontAttributes="Bold"
               HorizontalOptions="Center"/>

        <HorizontalStackLayout Spacing="10" HorizontalOptions="Center">
            <VerticalStackLayout>
                <ImageButton x:Name="ImgBtn1"
                             Source="rottenps.jpg"
                             HeightRequest="150"
                             Clicked="OnImage1Clicked"/>
                <Label Text="Expectation" HorizontalOptions="Center"/>
            </VerticalStackLayout>

            <VerticalStackLayout>
                <ImageButton x:Name="ImgBtn2"
                             Source="freshp.webp"
                             HeightRequest="150"
                             Clicked="OnImage2Clicked"/>
                <Label Text="Reality" HorizontalOptions="Center"/>
            </VerticalStackLayout>
        </HorizontalStackLayout>
    </VerticalStackLayout>

</ContentPage>
