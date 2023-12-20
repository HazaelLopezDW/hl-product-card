# hl-Product-card

Este es un paquete de pruebas de despliegue en NPM

### Hazael López Díaz

## Ejemplo
```
    import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'hl-product-card'
```

```
    <ProductCard 
        product={product}
        initialValues={{ 
            count: 4,
            // maxCount: 10
        }}
    >
        {
            ({reset, increaseBy, isMaxCountReached, count, maxCount}) => (
            <>
                <ProductImage  />
                <ProductTitle  />
                <ProductButtons />
            </>
            )
        }
    </ProductCard>
```