# Media Queries

	"phone":        400px,
	"phone-wide":   480px,
	"phablet":      560px,
	"tablet-small": 640px,
	"tablet":       768px,
	"tablet-wide":  1024px,
	"desktop":      1248px,
	"desktop-wide": 1440px

	@include media("<desktop") {
		
	}

	@include media(">phone", "<desktop") {
	
	}

# Mixins

## Центрирование блочного элемента
	@include push--auto; 
## Сниппет для псевдо-элемента
	@include pseudo;
## Для пропорционального увеличения
	@include responsive-ratio(16,9);
## Почти параллакс эффект
	@include background-fixed("path")

